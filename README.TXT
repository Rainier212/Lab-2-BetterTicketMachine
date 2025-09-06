Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.

ANSWERS TO QUESTIONS:

47. The balance shouldn't change in cases when an error message is printed. If I enter the value 0 as the parameter, it wouldn't change the balance. After entering the value 0, it showed me a message saying "Use a positive amount rather than: 0".

48. I think it will accept the 0 now. After testing, the method accepts 0 and positive amounts instead of just positive amounts superior to 0.

50. I believe it was the isVisible feature. Yes because the object can either be visible or invisible, not both.

51. In the naive-ticket-machine, it's total = total + balance. In the better-ticket-machine it's balance = balance - price. The better-machine-ticket does a better job at managing the balance since it deducts the cost of a ticket, meaning there will be a remainder if balance>ticketprice. This wouldn't be the case in the naive-ticket-machine.

52. Yes, it will still be able to be compiled. When printing without inserting money, it will print the ticket and also deduct the price from our balance, giving us a negative balance.

53. I don't think it can be ever set to a negative value since the operation balance = balance - price only excecutes if balance >= price.

54. Multiplication, division and modulus.

55. saving = price * discount;

56. mean = total / count;

58. They are both the same in my opinion, so they're both equally easy to understand.

59. The original returns the balance first then sets it to zero. The flawed one does the opposite; it sets the balance to zero and then returns it.

60. It will give me an error stating that balance = 0 is an unreachable statement.

61. The difference is that there is now a int in the price field. Yes, this version is able to be compiled. When inspecting, I noticed that the price is 0 instead of the value I inputted which was 100. I'm not so sure how to explain this effect, but I think it has to do with the int before the price field.

64. For this challenge, I wasn't able to complete it. I didn't really understand what and how to do it after searching online. I would send a Mio, but at the time I'm doing this, it's already pretty late. Sorry! 
