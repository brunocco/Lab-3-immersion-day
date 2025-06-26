# Lab-3-immersion-day
Passo a passo do Laboratório do evento Immersion day focado na criação e configuração do AWS S3

# Amazon S3 Hands-On Lab
<img src="assets/s3-icon.png">

## Visão geral do Amazon S3
O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e desempenho líderes do setor. Ele pode ser usado para armazenar e recuperar qualquer quantidade de dados, a qualquer hora, de qualquer lugar na web.

Este laboratório foi desenvolvido para lhe dar alguma experiência na interação com o serviço S3 por meio do Console da AWS e demonstrar o caso de uso de acesso seguro a objetos dentro de um bucket S3 privado por meio de um host da Web EC2.

## Este laboratório orientará você sobre o seguinte:
- Criando um bucket no S3
- Adicionando objetos ao seu bucket S3
- Trabalhando com objetos no console S3
- Acessando objetos armazenados no S3
- Habilitando o controle de versão do bucket
- Configurando uma Política de Ciclo de Vida
- Limpeza: Excluindo os objetos e o bucket S3

## Legenda do texto do laboratório
- "Texto citado" - Faz referência a um título, cabeçalho ou nome no console.
- **Texto em negrito** - Representa um botão, link ou menu suspenso no qual você precisará clicar ou selecionar.
- Inline code- Texto que você precisa copiar para entrada (textos mais longos terão um botão de cópia, textos mais curtos serão apenas destacados).
- Inline code [with brackets]- O texto entre parênteses representa o texto que requer uma entrada única. A entrada necessária será indicada entre parênteses.

## Duração do laboratório
Este laboratório levará cerca de 1 hora para ser concluído.

## 💰 Custos de Laboratório

| Categoria               | Custo por hora | Custo mensal |
|-------------------------|----------------|---------------|
| Amazon S3 (fotos)       | $0,00          | $0,00         |
| Amazon EC2 - t2.micro   | $0,0116        | $8,47         |

**Custo total do workshop:** US$ 0,50 – US$ 1,00
> 💲 [Calculadora de preços AWS](https://calculator.aws/#/)

## Pré-requisitos:
Se quiser visualizar as imagens carregadas no seu bucket S3 e ver o versionamento em ação posteriormente no laboratório, você precisará de um host web. Este recurso de host web permitirá que você interaja com o seu bucket S3 em um ambiente real. Clique no link do modelo abaixo para criar o host web no EC2 usando o CloudFormation. .

## Baixe e inicie o modelo CloudFormation

Baixe o modelo CloudFormation aqui [Baixar S3-General-ID-Lab.yaml](https://github.com/brunocco/Lab-3-immersion-day/raw/main/Yaml%20para%20baixar/S3-General-ID-Lab.Yaml) e salve-o no seu disco rígido local.

Agora abra o CloudFormation serviço.
