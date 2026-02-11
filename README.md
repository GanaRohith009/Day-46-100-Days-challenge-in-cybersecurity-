# Day-46-100-Days-challenge-in-cybersecurity-
### Day 46: Styling HTML - Why 3 Ways Exist

Today’s focus was on understanding the architectural evolution of CSS and the specific use cases for the three styling methods.

#### 📁 Content Overview
- **Inline CSS (The Quick Fix):** Explored how `style` attributes provide immediate results but lead to "tight coupling," making code difficult to maintain. Best used today for dynamic JS-driven styles.
- **Internal CSS (The First Level of Organization):** Analyzed how `<style>` tags in the `<head>` introduced the DRY (Don't Repeat Yourself) principle for single documents.
- **External CSS (The Scalable Solution):** Focused on the professional standard. Key benefits include:
    - **Separation of Concerns:** Keeping HTML (content) separate from CSS (presentation).
    - **Browser Caching:** Significant performance wins for multi-page sites.
    - **Global Maintainability:** Implementing site-wide changes from a single `.css` file.

#### 💡 Key Insight
| Method | Focus | Best For |
| :--- | :--- | :--- |
| **Inline** | Speed | Dynamic JS updates |
| **Internal** | Organization | Standalone pages / Emails |
| **External** | Scalability | Professional Web Apps |

---
