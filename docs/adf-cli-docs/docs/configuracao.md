# Configuração

Esta ferramenta utiliza o arquivo de configuração .adf.toml para definir valores para variáveis de configuração. O local default é seguinte para cada plataforma:

- GNU/Linux e macOS: $HOME
- Windows: %USERPROFILE%

## Opções de configuração:

- web.port: Número de porta TCP a ser utilizada pelo ADF Web. Default: 8051

## Exemplo de arquivo de configuração

```toml
[web]
port = 8051
```
