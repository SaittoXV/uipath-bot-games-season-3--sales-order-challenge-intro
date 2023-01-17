# uipath-bot-games-season-3--sales-order-challenge-intro
Validating orders is a time-consuming process for Catchy Components. They desperately need a bot to automate the process of validating orders to improve their customer experience and send invoices out in a timely fashion. The Bot must start by launching the challenge page. From there, the bot needs to launch the organization's sales order application, and navigate to the Sales Order tab, and start validating orders.

For each order with a status of “Confirmed” or “Delivery Outstanding” - the bot needs to expand the order by clicking the “+” button

    For each item included in the order, the bot needs to perform a lookup in the tracking details in the Global Express tracking website – the world’s premier fictitious shipping provider
    If the status for all items is “Delivered” - the bot needs to click the “Generate Invoice” button for the entire order
    If one or more items from the order are not yet delivered, no action should be taken on this order.

Once all orders have been checked, the bot should click the “Export” button in the top right corner of the Sales Order app to generate a sales order report that should be uploaded in the Sales validation section of the challenge page. Challenge Page URL: https://developer.automationanywhere.com/challenges/salesorder-challenge.html
