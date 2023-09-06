
<img width="334" alt="Screenshot 2023-09-06 at 6 09 49 PM" src="https://github.com/gouravZenefits/BookmarkUrlExtension/assets/96715717/cf8708e6-9bd4-4acd-856a-206569b5f345">

**What**
  - It's an extension to update the base url of all the urls we have stored as a bookmark.

**Why**
  - To reduce time consume while copying/pasting/updating the base url every time we check spoof/prod/alpha/beta urls.

**How to Install**
- This can be use in both edge and chrome. For installing we need to turn on the developer mode of browser.
    - Clone this repo, using git clone <git_url>
    - Click on Manage Extension button on edge
      <img width="709" alt="Screenshot 2023-09-06 at 1 19 34 PM" src="https://github.com/gouravZenefits/UrlExtension/assets/96715717/6563fa54-b4e1-48b0-be02-0ff625c3d5be">
    - Turn on Developer Mode
      <img width="1727" alt="Screenshot 2023-09-06 at 1 21 51 PM" src="https://github.com/gouravZenefits/UrlExtension/assets/96715717/e2d496c1-2152-4a2d-a359-a37b0d28f61b">
    - Click on Load Unpacked
      <img width="1727" alt="Screenshot 2023-09-06 at 1 24 46 PM" src="https://github.com/gouravZenefits/UrlExtension/assets/96715717/0f6b38a2-47fe-4805-a9dd-24a4fd7a2ddb">
    - Select the folder where repo has been cloned
    - Hurray! your extension has been added.
 
**How to Use**
- If we have these urls as boomark:
    - https://defkey.com/iterm-shortcuts
    - https://console.zenefits.com/console/company/119883
    - https://console.zenefits.com/console/object_detail/7558147/benefits_transaction.models.BenefitsTransaction
- If I pass Prod url as https://console.zenefits.com/ and Spoof url as https://gbarnwal-spoof-61650.dev.zncloud.net/ and click on "Update" button. 
- We will change all the above bookmark urls as below:
    - https://defkey.com/iterm-shortcuts
    - https://gbarnwal-spoof-61650.dev.zncloud.net/console/company/119883
    - https://gbarnwal-spoof-61650.dev.zncloud.net/console/object_detail/7558147/benefits_transaction.models.BenefitsTransaction
- To change the base url to old state, we just need to click on "Swap" button first and then "Update" button.
