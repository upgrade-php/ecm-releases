# ECM - releases

Este repositorio publica apenas os binarios e os instaladores do ECM (Sistema de Engenharia de Contexto para Marketing). O codigo-fonte nao fica aqui.

## Instalar

Windows (PowerShell):

```powershell
irm https://github.com/upgrade-php/ecm-releases/releases/latest/download/install.ps1 | iex
```

macOS e Linux:

```sh
curl -fsSL https://github.com/upgrade-php/ecm-releases/releases/latest/download/install.sh | sh
```

Depois, em qualquer pasta:

```sh
ecm criar "Nome do Negocio"
```