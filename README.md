
# Discount Calculator Pro

This is a powerful and responsive client-side tool designed to calculate prices with complex discounts across multiple products, featuring local storage management and rich text export capabilities.

## 🌟 Key Features

### 1. Advanced Product Calculation

-   **Multi-Product Support:** Easily add and manage a list of products.
    
-   **Flexible Discounting:** Apply discounts per product using one of three methods:
    
    -   **Percentage (`% Disc`):** Apply a percentage reduction to the subtotal.
        
    -   **Amount (`₹ Amt`):** Apply a fixed currency amount reduction.
        
    -   **Final Price (`Final ₹`):** Specify the exact final price; the discount is calculated automatically.
        
-   **Real-Time Totals:** The Grand Total, Total Savings, and Overall Discount Percentage are calculated instantly as you input values.
    

### 2. Local Quote Management (Save & Load)

The Quote Management section allows you to save your current product list and calculations for later retrieval, using your browser's local storage.
|Feature  |  Action|Behavior|
|--|--|--|
|**Save Quote**  |  Click `💾 Save Quote`|Saves the current list under the entered Quote Name. **The screen is automatically cleared, and a success message is displayed** after a successful save.|
|**Load Quote**|Type a saved name into the input field or select it from the dropdown.|If a saved name is detected, the corresponding product list and calculations are loaded onto the screen.|
|**Clear Quote**|Click `✨ Clear Quote`|Clears all product inputs and the Quote Name field, preparing the screen for a new quote.|
|**Delete Quote**|Click `🗑️ Delete Quote`|Permanently removes the named quote from local storage. This button is only enabled when a saved quote is currently loaded.|

### 3. Sharing and Export

Use the action buttons at the bottom to quickly share or copy your finalized quote.

-   **Copy Price Quote:** Copies the full summary, including all product details and the Grand Total, to your clipboard. The copied text uses **rich text formatting** (bold and italics) suitable for pasting into messaging apps like WhatsApp, Slack, or email, ensuring clear presentation.
    
-   **Share via WhatsApp:** Opens a new WhatsApp share window with the formatted quote text pre-filled, ready to send to a contact.
    

### 4. User Feedback

The application provides non-intrusive pop-up messages at the bottom of the screen to confirm key actions, such as saving, loading, or clearing a quote.
