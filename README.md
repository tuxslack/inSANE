
**inSANE** é um script de escaneamento simples que usa SANE para escanear imagens.

Sua configuração padrão é escanear imagens em ~/Imagens/Escaneados com uma resolução de 600 DPI, mas isso pode ser configurado com o arquivo ~/.insane.conf com esta estrutura.

```
Pasta=~/Imagens/Escaneados
Resolucao=300
```


## Instalação:

Extrair o arquivo .tar.gz
```
tar -xvf insane.tar.gz

cd insane
```

## Informe a senha de Root:
```
su -c "mv -i insane.sh    /usr/local/bin/insane.sh"


mv -i digitalizar.desktop .local/share/applications/digitalizar.desktop
```

## Como usar:

menu iniciar => Gráficos => Digitalizar documentos


## Remoção:

```
rm -Rf ~/.local/share/applications/digitalizar.desktop

su -c "rm -Rf /usr/local/bin/insane.sh"
```
