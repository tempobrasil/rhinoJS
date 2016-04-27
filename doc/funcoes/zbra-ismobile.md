# Função zbra.ismobile

Verifica se o dispositivo que está sendo usado é um celular.

## Retorno
Retorna um _boolean_, onde _true_ se for de um celular e _false_ de for de um computador.

## Exemplo

    if(zbra.device.isMobile()){
        alert('É um celular.');
    } else {
        alert('É um computador.');
    }