## Modum Craft


_Modum Craft_  is a QA tool for exchanges and financial marketplaces.

**For Whom**  
Modum is expetced to be used to exercise test systems at a market place.  
  
**What problems can Modum Craft solve?**  

-   Members want to test their systems, algos and ideas. market places often provide a test arena   but the members often don t have anything to trade with. With Modum, you can easily create a realistic environment for member testing. Modum will continuously inject orders and update the order book so that the member system has something against which to trade.

-   A marketplace can use Modum to do many different kinds of technical testing: operational scenarios such as failover, system integrity, performance evaluation, load testing and capacity planning.
-   By using predetermined scripts, Modum can be used for compliance, performance and regression testing.

**Deploying Modum Craft**

-   Modum will connect to the target environment in the same way as a member through any of the API s provided by the marketplace. It does not need any privileged access and has a minimum of dependencies. No commercial third party components are used. There is no need to change or adapt any of your existing systems.
-   The Modum traffic generator is extremely lightweight. A Modum instance can generate 10 thousand transactions per second. Modum can be run in one or many parallel copies to achieve the transaction rates you need. Modum is designed to be run in a cloud for easy scaling.

**Scripting**

-   Modum requires that you design a script. A script consists of small building blocks, where each block can be a definition of a single transaction or be micro scenarios containing a sequence of transaction. You can freely combine these building blocks into complex scenarios spanning everything from seconds to a full trading day and covering the simulation of a single instrument or the full market.
-   Scripts can be written for normal steady state trading or for special market scenarios that are of interest such as periods of extreme volatility and volume. Once you start a script, Modum will simulate traffic consistent with the script.
-   Modum comes with a set of predefined scripts that illustrate different market conditions. These scripts are created from real trade data and can be used either for a testing session across a whole trading day, or can be inserted into another script to illustrate a particular market behavior.


**Further..**
More information and downloads  are available at [https://www.hoddmimes.com/modum](https://www.hoddmimes.com/modum/modumindex.htm)

