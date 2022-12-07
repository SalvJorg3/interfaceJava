Solution of the problem:

A Brazilian car rental company charges a fee for rentals of up to 12 hours. However, if the duration of the rental exceeds 12 hours, the rental will be charged on a daily basis. In addition to the rental price, the tax is added to the price according to the country's rules, which in Brazil is 20% for amounts up to 100 reais or 15% for amounts above 100 reais. Write a program that reads the lease data (car model, start and end times of the lease) as well as the hourly and daily lease amounts. The program must then generate a payment note (containing the lease amount, tax amount and total payment amount) and inform the data on the screen.

1st commit - solution does not use an interface, revealing the dependence on future changes in case there is a change in the BrazilTazService class

2nd commit - solution uses the TaxService interface which, in the main code, performs an upcasting of the BrazilTaxService Class.


Solução do problema: 

Uma locadora brasileira de carros cobra um valor para locações de até 12 horas. Porém se a duração da locação ultrapassar 12 horas, a locação será cobrada com base em um valor diário. Além do valor da locação, é acrescido no preço o valor do imposto conforme as regras do país que no Brasil é de 20% para valores até 100 reais ou 15% para valores acima de 100 reais. Fazer um programa que lê os dados da locação (modelo do carro, instante inicial e final da locação) bem como o valor por hora e o valor diário de locação. O programa deve então gerar a nota de pagamento (contendo o valor da locação, valor do imposto e valor total de pagamento) e informar os dados na tela. 

1º commit - solução não utiliza interface, revelando a dependência de alteração futura caso haja mudança na classe BrazilTazService 

2º commit - solução utiliza interface TaxService que no código principal realiza um upcasting da Classe BrazilTaxService.
