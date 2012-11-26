### _For a discount on 2Checkout’s monthly fees, enter promo code:  GIT2CO  during signup._

### Integrate WP-Invoice with 2Checkout
----------------------------------------

### WP-Invoice Settings

1. Download the 2Checkout payment module at https://github.com/craigchristenson/2checkout-wp-invoice
2. Upload the files to your WP-Invoice directory on your web server.
3. Under **Invoice** -> **Settings**, select **2Checkout** for **Default Payment Method**.
4. Enter your **2Checkout Seller ID**. _(2Checkout Account Number)_ 
5. Enter your **2Checkout Secret Word**. _(Must be the same value entered on your 2Checkout Site Management page.)_
6. For demo sales set **Demo Mode** to **Yes**. For live sales keep **Demo Mode** at **No**.
7. Copy the URL provided under "2Checkout Approved URL/INS URL".
8. Click **Save All Settings**.

### 2Checkout Settings

1. Sign in to your 2Checkout account. 
2. Click the **Account** tab and **Site Management** subcategory. 
3. Under **Direct Return** select **Header Redirect** or **Given links back to my website**.
4. Enter your **Secret Word**._(Must be the same value entered in your WP-Invoice admin.)_
5. Paste the URL you copied from the "2Checkout Approved URL/INS URL" field in the Approved URL field.
6. Click **Save Changes**.
7. Under the Notification tab, paste the URL you copied from the "2Checkout Approved URL/INS URL" field in the Global URL field and enable all messages.
8. Click **Save Changes**.

Please feel free to contact 2Checkout directly with any integration questions.