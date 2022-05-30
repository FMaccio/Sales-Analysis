# Sales Analysis


### Project description:

As a newbie in the world of the data-analytics, I was commanded the task of analyzing the sales information of every sale made by an electronics Company in 2019.
In this Analysis the informations was presented as a List of Dictionaries. An exaple of one of them follows:

{  
  'Order ID': '209921',  
  'Product': 'USB-C Charging Cable',  
  'Quantity Ordered': '1',  
  'Price Each': '11.95',  
  'Order Date': '06/23/19 19:34',  
  'Purchase Address': '950 Walnut St, Portland, ME 04101'  
  }

The asignment was given in spanish, but the code can be followed and understood by anyone.
The goal of the analysis was to answer 10 questions regarding the clients behaviour when purchasing a product. 

#### Questions

**1)** ¿Cuál es el mes que reporta **la mayor cantidad de productos**?  
**2)** ¿Qué ganancia reporta dicho mes?  
**3)** ¿Qué porcentaje del total de las ventas representa?  
**4)** ¿Qué ciudad reportó la mayor cantidad de ventas?  
**5)** ¿Qué porcentaje del total de las ventas representa?  
**6)** ¿En qué horas del día se deberían publicar anuncios promocionales para maximizar las ventas?  
**7)** Determinar productos que se venden juntos y DE A DOS.  
**8)** ¿Cuál es el producto más vendido?  
**9)** ¿Cuál es la relación entre el precio del producto más vendido y el del menos vendido?  
**10)** ¿Cuál es la órden con mayor cantidad de productos?  

### Method
The method used to respond the questions is self explainaid by the humble code. For the mayority of the questions a list was created with the data that was needed for the question. 
For example, Q1 asks about the month with the most sales. It is here to take into account the difference between sale (dictionary) and order (id). In this case, there are as many sales as there are dictionarys. The insformation regarding the month could be obtained by chopping the Order Date until only having the month. Then, it was to count how many times a sale is made per month. Month 12 (december) was found to be the one with the most sales. The rest of the questions can be solved more or less in a similar way.


### Notes:

#### Note 1: 
There are meny repetitive proceses that could be simplyfied by a defining function. Since this is only a first draft of the solutions, there is a plan in place to defined the necesary functions and clean out the code.

#### Note 1: 
I couldn´t find a solution that was efficient or questions 7 and 10. My code made to many iterations thus it takes too long to get a result. I am open for suggestions in this regard. 

