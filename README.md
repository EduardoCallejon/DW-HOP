# DW-HOP

## Inicialização ##
Reunião de alinhamento para entender  quais indicadores necessitam, e onde estão situado os dados.

## Informações coletadas ##
1 - Os dados são de RH, o Dashboard será de relação de folha de pagamento.<br> 
2 - Os dados vem de planilhas em excel <br> 
3 - Necessitam dos dados todos os dias as 08:00 da manhã <br>
4 - Precisam entender a distribuição de salário por cargo, departamento e por período.

## Modelagem ##

Após a reunião e o alinhamento do projeto, é necessário montar um projeto de modelagem para obter a  melhor eficiência das tabelas e relacionamentos no DW. <br> 
Para isso, foi utilizado o próprio sistema SGBD do Posgresql, o Pgadmin, através dele é possível montar modelagens para o banco, conforme imagem abaixo;
<br>
<div align="center">
<img
src="https://github.com/user-attachments/assets/c45bf57f-0d4c-4ce9-84de-97d95f18c09d" width="700px" />
<br>
Fonte: Autoria Própria  
</div>

## Extração e Movimentação para o Banco staging area ##

No apache HOP, iniciamos pela extração dos dados que vem de 5 bases de Excel, é criado um Pipeline, utilizando as seguintes Steps;<br>
> 
>
>
>

A  imagem abaixo, demonstra um exemplo de como foi feito com uma das 5 bases;
<br>
<div align="center">
<img
src="https://github.com/user-attachments/assets/c45bf57f-0d4c-4ce9-84de-97d95f18c09d" width="700px" />
<br>
Fonte: Autoria Própria  
</div>

