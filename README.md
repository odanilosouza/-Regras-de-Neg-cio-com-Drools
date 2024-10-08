Instruções:

1. Assista ao vídeo:  
   - Acesse o vídeo para entender os conceitos apresentados e os passos necessários para a criação da aplicação.

2. Configuração do ambiente:  
   - Utilize o IntelliJ, Eclipse, NetBeans ou outra IDE de sua escolha.  
   - Crie um projeto Java usando Maven e adicione as dependências necessárias do Drools conforme mostrado no vídeo.

3. Estrutura do Projeto:  
   - No arquivo pom.xml, adicione as dependências do Drools e SLF4J, conforme demonstrado no vídeo.
   - Crie as pastas e arquivos Java necessários para representar o modelo de CNH e suas propriedades (número, nome, quantidade de pontos, data de expiração, etc.).
   
4. Implementação das Regras de Negócio:  
   - Crie um arquivo .drl (Drools Rule Language) para definir as regras de negócio.
   - As regras devem validar se:
     - A CNH está expirada.
     - A CNH tem mais de 20 pontos.
     - A CNH ainda não foi processada.
   - Cada regra deve ser testada de acordo com as condições do vídeo.

5. Processamento das CNHs:  
   - Implemente o código Java que envia os objetos CNH para o Drools processar as regras e modificar o status das CNHs (válida ou inválida).
   
6. Testes e Validação:  
   - Teste a aplicação com diferentes exemplos de CNHs (como no vídeo) e verifique se as regras estão sendo aplicadas corretamente.
   - Utilize System.out.println para exibir o resultado final, mostrando o status e a causa da invalidação (expirada, muitos pontos, etc.).

7. Documentação:  
   - Documente o código explicando a lógica utilizada para definir as regras de negócio e como o Drools foi configurado.

Critérios de Avaliação:
- Corretude do código: A aplicação deve processar as CNHs corretamente de acordo com as regras estabelecidas.
- Estrutura do projeto: O projeto deve seguir a estrutura apresentada no vídeo, com as dependências e configuração corretas.
- Clareza na documentação: A documentação deve explicar de maneira clara as regras de negócio e como o Drools foi configurado e utilizado.
- Testes: Diferentes CNHs devem ser testadas e os resultados exibidos no console.

Entrega:
Submeta o código da aplicação e a documentação em um repositório do GitHub
