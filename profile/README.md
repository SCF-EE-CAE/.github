# Sistema Ciberfísico de Eficiência Energética e Condicionamento Ambiental 

O conforto térmico em ambientes internos, como escritórios, é crucial para assegurar o bem-estar dos ocupantes. A falta de conforto térmico pode não apenas comprometer a saúde em situações extremas, mas também afetar a concentração, causando desconfortos como dores de cabeça. Tradicionalmente, o ar condicionado é o sistema mais utilizado para manter esse conforto, mas seu uso inadequado pode resultar em um consumo de energia maior do que o necessário.

Nosso projeto propõe uma solução automática de controle ambiental capaz de monitorar variáveis como temperatura, umidade relativa e o consumo de energia dos dispositivos de climatização. O sistema deve ajustar-se continuamente às necessidades térmicas dos ocupantes, considerando o feedback fornecido por eles. O objetivo é garantir o conforto térmico com o menor consumo energético possível.

## Repositórios principais do sistema

- [TBENV](https://github.com/SCF-EE-CAE/TBENV): Código do módulo ambiental, responsável pelo monitoramento de variáveis como temperatura e umidade utilizando diversos sensores.
- [TBENE](https://github.com/SCF-EE-CAE/TBENE): Módulo de monitoramento energético, focado na análise do consumo dos equipamentos de climatização.
- [TBIRC](https://github.com/SCF-EE-CAE/TBIRC): Software para o controle do ar condicionado via emissor IR.
- [TBPWC](https://github.com/SCF-EE-CAE/TBPWC): Software de controle de relés para dispositivos diversos, permitindo o gerenciamento de aparelhos elétricos.
- [TBUIF](https://github.com/SCF-EE-CAE/TBUIF): Interface de usuário do sistema, oferecendo feedback sobre sensação térmica e gráficos de monitoramento.
- [TBCTR](https://github.com/SCF-EE-CAE/TBCTR): Software de controle ambiental que interage com a plataforma Thingsboard para coletar informações e atuar no ambiente.
- [utilities](https://github.com/SCF-EE-CAE/utilities): Ferramentas auxiliares para o funcionamento e uso do sistema.
