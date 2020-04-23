**Os 11 Mandamentos de Componentização Angular**

1. **Independente:** Não interfere ou depende dos outros 
2. **Adaptativo:** Não faz requisições a recursos externos, podendo copiar e colar em outro lugar
3. **Ininterrupto:** Seus erros não interferem no sistema pai 
4. **Hipovalorado:** Não pode ocorrer erros ao não receber alguma propriedade, só não executar nada, todo os valores devem iniciar com default
5. **Hipervalorado:** Todas suas propriedades são parametrizados 
6. **Visualmente Independente:** Seu estilo não depende do pai, mas o pai pode definir seu estilo
7. **Infixável:** Não existem valores fixos, sejam eles casas decimais, largura... (seguindo o mandamento 4)
8. **Inregravel:** Não pode ter regras de negócio específica de 1 sistema 
9. **Dinamicidade:** Não fazer depende número finito de propriedades (var1, var2 fazer recebimento de lista)
10. **Nomeação Autoexplicativa:** Nome e parâmetros devem ser totalmente autoexplicativa sem a necessidade de consultas externas 
11. **Expansível:** O componente deve ser de alta manutenbilidade e expansão sem alterar funcionalidades anteriores
