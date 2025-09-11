### Build a Cash Register
Here you'll build a cash register app that will return change to the customer based on the price of the item, the amount of cash provided by the customer, and the amount of cash in the cash drawer. You'll also need to show different messages to the user in different scenarios, such as when the customer provides too little cash or when the cash drawer doesn't have enough to issue the correct change.

<sub>:bulb: Your application should show different messages depending on the price of the item, the amount of cash provided by the customer, and the amount of cash in the drawer:</sub>

- <sub>`"Status: INSUFFICIENT_FUNDS"`: if `cash-in-drawer` is less than the change due, or if you cannot return the exact change.
- <sub>`"Status: CLOSED"`: if `cash-in-drawer` is equal to the change due.
- <sub>`"Status: OPEN"`: if `cash-in-drawer` is greater than the change due and you can return change, with the change due in coins and bills sorted in highest to lowest order.</sub>

<br />

|Currency Unit      |            Amount|
|:-----------------:|:----------------:|
|Penny              |     $0.01 (PENNY)|
|Nickel             |    $0.05 (NICKEL)|
|Dime               |       $0.1 (DIME)|
|Quarter            |   $0.25 (QUARTER)|
|Dollar             |          $1 (ONE)|
|Five Dollars       |         $5 (FIVE)|
|Ten Dollars        |         $10 (TEN)|
|Twenty Dollars     |      $20 (TWENTY)|
|One Hundred Dollars|$100 (ONE HUNDRED)|

**Objective:** Build an app that is functionally similar to https://cash-register.freecodecamp.rocks

**User Stories:**

- You should have an `input` element with an `id` of `"cash"`
- You should have a `div`, `span` or `p` element with an `id` of `"change-due"`
- You should have a `button` element with an `id` of `"purchase-btn"`
- When the value in the `#cash` element is less than `price`, an alert should appear with the text `"Customer does not have enough money to purchase the item"`
- When the value in the `#cash` element is equal to `price`, the value in the `#change-due` element should be `"No change due - customer paid with exact cash"`
- When `price` is `19.5`, the value in the `#cash` element is `20`, `cid` is `[["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be "Status: OPEN QUARTER: $0.5"
- When `price` is `3.26`, the value in the #cash element is 100, `cid` is `[["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: OPEN TWENTY: $60 TEN: $20 FIVE: $15 ONE: $1 QUARTER: $0.5 DIME: $0.2 PENNY: $0.04"`
- When `price` is `19.5`, the value in the #cash element is `20`, `cid` is `[["PENNY", 0.01], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: INSUFFICIENT_FUNDS"`
- When `price` is `19.5`, the value in the `#cash` element is `20`, `cid` is `[["PENNY", 0.01], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 1], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: INSUFFICIENT_FUNDS"`
- When `price` is `19.5`, the value in the `#cash` element is `20`, `cid` is `[["PENNY", 0.5], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: CLOSED PENNY: $0.5"`

Happy Coding!
