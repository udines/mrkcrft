# Mrk Crft
This is a learning project. I'm building a web app to sell watch straps for the watch nerds. I will document the process of the development in this repo. There will be several phase of the development including:
- Requirements
- UI design
- System design
- Assets gathering
- Code
- Testing and bug fixes
- Deployment
- Start selling
- Improvements
The purpose of this project is to test my ability to build a small business from ideation to creation to market. 

## Requirements
There are two roles of user in this app: buyer and admin. Each of those role has different capability.

**Buyers**:
- Buyer can choose watch straps to view. Products will be displayed as grid. 
- Each product item consists of thumbnail image, name, price, and buy buttons.
- Buyer can view product in detail, including: photos, price, available size, description, and buy buttons.
- Buyer can view enlarged image. Other images will be displayed as thumbnail below the enlarged image. Buyer can choose which image to enlarge.
- Buyer can choose watch strap size. Size is the width of the strap and is related to the lug width of a watch.
- Buyer can click buy button and will be redirected to the corresponding marketplace.
- There are two buttons available. Buy in Tokopedia and Buy in Shopee.
- Buyer can virtually simulate a combination of watch strap and selected watches.
- Buyer can change the watch and strap for the simulation.
- Available watches depends on the strap size the buyer choose. Some watch have 18mm, 19mm, 20mm, or 22mm lug width.
- Customizing the combination will also change the selected strap and size on the previous step.

**Admins**:
- Admin has to login with registered credentials to access the admin panel.
- Admin can add, modify, or delete products.
- Admin can change the link on the buy button of a product to corresponding marketplace.
- Admin can set available sizes and the count of a product.
- Admin can add, modify, or delete images and thumbnail of a product.
- Admin can change price of a product.
- Admin can change description of a product.
- Admin can add or remove watches for the simulation.
- Admin can set the watches lug width.