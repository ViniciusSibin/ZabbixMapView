# ZabbixMapView

Um sistema de visualização geográfica de rede integrado com o Zabbix, voltado para operadoras de internet e provedores de backbone. Esse projeto permite desenhar rotas de fibra ótica e posicionar equipamentos diretamente em um mapa interativo (Google Maps ou Leaflet), exibindo em tempo real o status de tráfego, rompimentos e dados como latência, temperatura, tensão e status da rede elétrica dos equipamentos monitorados.

## ✨ Principais funcionalidades (MVP)

- Desenho de rotas de backbone diretamente no mapa
- Indicação visual do estado da rota (normal, sobrecarregada ou rompida)
- Posicionamento de sensores e equipamentos (com base em coordenadas GPS)
- Exibição de métricas de cada equipamento usando dados coletados via API do Zabbix
- Atualização periódica das informações para manter o painel dinâmico

## 🎯 Objetivo

Fornecer uma visualização clara e intuitiva do estado da infraestrutura de rede física, facilitando a tomada de decisões rápidas em casos de falhas, gargalos ou rompimentos. Ideal para ISPs e empresas que utilizam Zabbix como plataforma de monitoramento.

## 🛠️ Tecnologias utilizadas

- **Frontend**: HTML, CSS, JavaScript (com Leaflet.js ou Google Maps API)
- **Backend**: Python ou PHP (com integração via Zabbix API)
- **Monitoramento**: Zabbix (qualquer versão compatível com a API)
- **Banco de Dados (opcional)**: MariaDB ou SQLite para armazenar rotas e configurações locais

## 🚀 Status do Projeto

> Protótipo em desenvolvimento para aplicação real com redes de pequeno porte. Este projeto está sendo desenvolvido como parte de uma consultoria para provedores regionais, e será evoluído em fases.

## 📌 Próximos passos

- Interface para cadastro e edição de rotas
- Autenticação de usuários
- Cache de métricas para otimizar chamadas à API do Zabbix
- Responsividade para tablets e mobile

## 📷 Prints e demonstrações

(⚠️ Adicione aqui screenshots ou GIFs curtos com visual da ferramenta em funcionamento assim que tiver.)

---

Desenvolvido por [Vinicius Sibin](https://github.com/teuGitHubAqui) 🧠🚀  
