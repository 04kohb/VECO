# VECO


public boolean transfer(bankaccount destination, double amount)

if(this.money >= amount) 
{
    this.money -= amount;
    other.money += amount;
    return true;
}
return false;
