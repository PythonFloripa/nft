# **Projeto NFT Python Floripa**

## Resumo do Projeto

O projeto de NFT da comunidade Python Floripa visa desenvolver uma plataforma colaborativa para criar, resgatar e validar NFTs, com foco na capacitação dos membros da comunidade e na aplicação prática de tecnologias blockchain. A ferramenta será utilizada inicialmente pela comunidade Python Floripa, porém estará aberta a outras comunidades e organizações públicas e privadas, permitindo a difusão de NFTs e blockchain de forma acessível e prática.

## Objetivos Principais

1. **Capacitação dos membros:** Criar oportunidades para que desenvolvedores da comunidade Python Floripa aprendam e implementem soluções blockchain.  
     
2. **Conteúdo de referência:** Produzir documentação e conteúdo que sirvam como referência para a comunidade em geral.  
     
3. **Plataforma de NFTs:** Desenvolver uma plataforma de ponta a ponta que integre um provedor de blockchain, como Ethereum, para permitir o cadastro, resgate e validação de NFTs.  
     
4. **Aplicações práticas:** Criar soluções práticas como:  
* Certificados de participação em eventos, gerados automaticamente com base no check-in dos participantes.  
* NFTs de cards para eventos e palestras, permitindo que participantes resgatem NFTs personalizados com base na sua presença.

**Certificado de Participação via NFT**: Cada participante que fizer check-in em um evento da Python Floripa poderá resgatar um NFT como certificado digital, garantindo a autenticidade de sua participação.  
**Cards NFT para eventos e palestras**: Cada evento ou atividade da comunidade terá um card digital vinculado a um NFT, que poderá ser resgatado por participantes após validação do check-in.  
**Popularização da Blockchain**: Facilitar a compreensão e utilização da tecnologia blockchain por parte da comunidade e da sociedade em geral, aproximando os desenvolvedores da prática e fomentando a difusão desse conhecimento.

## Objetivos Específicos

1. **Ferramenta para várias comunidades:** A plataforma será disponibilizada publicamente e poderá ser utilizada por outras comunidades interessadas, mediante a compra de créditos para cobrir os custos de infraestrutura, como o pagamento ao provedor de blockchain.  
     
2. **Desenvolvimento colaborativo:** Todo o código-fonte será desenvolvido de forma colaborativa e aberto no GitHub da comunidade Python Floripa.  
     
3. **Construção de autoridade:** Participantes diretos do desenvolvimento poderão adicionar suas contribuições ao projeto em seus portfólios, destacando sua participação para fins de progressão profissional.  
     
4. **Documentação e Live Weeklys:** O desenvolvimento será documentado e acompanhado por transmissões semanais ao vivo entre os membros do squad de desenvolvimento, para discutir a evolução, distribuir demandas e relatar a evolução do projeto. Essas lives serão disponibilizadas no YouTube da comunidade.

## Especificação Técnica

### Estrutura da Plataforma

1. **Backend:** A plataforma será desenvolvida em Python, com integração a um provedor de blockchain (e.g., Ethereum). Será responsável por:  
* Gerenciar o cadastro dos eventos e usuários.  
* Verificar o check-in dos participantes nos eventos.  
* Emitir e associar NFTs aos participantes.  
    
2. **Frontend:** Interface simples e amigável para permitir que os usuários façam o resgate dos NFTs gerados. O design será responsivo, permitindo fácil acesso em diferentes dispositivos.  
     
3. **Integração com Blockchain:** A plataforma terá integração com o blockchain escolhido (e.g., Ethereum) para a criação e validação dos NFTs. Utilizaremos smart contracts para garantir a segurança e transparência das transações.  
     
4. **Banco de Dados:** Sistema de banco de dados para armazenar os eventos, usuários, e NFTs gerados, garantindo a rastreabilidade e segurança dos dados.

### Cronograma e Marcos do Projeto

1. **Planejamento e Design** (prazo?):  
* Definir os requisitos detalhados.  
* Estruturar o backend e a integração com o blockchain.  
* Prototipar a interface.  
    
2. **Desenvolvimento** (prazo?):  
* Implementação do backend e frontend.  
* Configuração da integração com o blockchain.  
* Testes iniciais com a comunidade.  
* Publicar documentação no GitHub.  
    
3. **Lançamento Beta** (prazo?):  
* Disponibilizar a versão beta da plataforma para testes com os membros da comunidade.  
    
4. **Ajustes e Lançamento** (prazo?):  
* Correção e ajustes de código.  
* Realizar lives de apresentação da solução.  
* Recrutar embaixadores para divulgar o projeto em eventos diversos.  
* Divulgação nas redes sociais e eventos da comunidade.

## Referencias

**Benchmark**
[https://poap.xyz/](https://poap.xyz/) 

**Ferramentas para Desenhar Arquitetura** 
draw.io  
[https://structurizr.com](https://structurizr.com/)  
 
## Comentários e Devaneios

## Requisitos funcionais

- Usuário

- Eventos
  - tipos de usuários:
    - admin
    - apoio
    - palestrante
    - participante
  - check-in
    - self service?

- Atividade
  - check in
  - QR code no meio da atividade

- Certificados
  - certifica que participou das atividades do Eventos

## Requisitos não-funcionais
- deploy na AWS (?)


