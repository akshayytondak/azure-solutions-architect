# Adding a Custom Domain to AAD

1. Log in to the Azure Portal at portal.azure.com

![image1](https://github.com/akshayytondak/azure-solutions-architect/blob/main/labs/image/1.png?raw=true)

2. Click the Azure Active Directory link, select Custom Domain Names, select + Add Custom Domain, enter your custom domain in the Custom Domain Name text box, and click the Add Domain button.

![image2](https://github.com/akshayytondak/azure-solutions-architect/blob/main/labs/image/2.png?raw=true)

3. Log in to your domain hosting provider and add the preferred DNS record that validates that you own the domain.

4. Once you've added the record, click the Verify button. It can take up to 72 hours for the Domain Name System (DNS) change to propagate, but it usually takes much less time. In my scenario, it took less than five minutes.

![image3](https://github.com/akshayytondak/azure-solutions-architect/blob/main/labs/image/3.png?raw=true)

5. Once it's verified, click the Make Primary button and then Yes.

6. Navigate back to the Azure Active Directory link. Select Custom Domain Names, and you will see the new custom domain marked as Primary as well as the default tenant.

