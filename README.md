# Lynx Browser

Navegador baseado no Firefox com identidade própria.


## Como funciona

O GitHub Actions compila automaticamente quando você faz push na branch `main`.

## Estrutura

```
lynx-browser/
├── .github/workflows/build.yml   ← workflow de compilação
├── branding/
│   └── lynx-logo.png             ← sua logo (coloque aqui)
├── config/
│   ├── mozconfig                 ← opções de compilação
│   └── home.html                 ← página inicial/nova aba
└── patches/
    └── branding.patch            ← patches extras (opcional)
```

## Para compilar

1. Faça push na branch `main`
2. Vá em **Actions** no GitHub
3. Aguarde o build (leva ~2-3h)
4. Baixe o binário em **Releases**

## Para atualizar

Edite qualquer arquivo e faça push — o Actions recompila automaticamente.
