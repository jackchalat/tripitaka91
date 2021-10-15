# CSS class reference
Each article in Tripitaka is represented as an html file. The class names follows Block Element Modifier convention.

`.chapter` an article block in Tripitaka. Since each article can be referred as a sutta or a short section. This may change later.  
`.chapter__header-title` an element for the article header. Each article has `.chapter__header-title` as the first child.  
`.chapter__summary` an element for the article summary.  Each article has `.chapter__summary` as the second child.  
`.chapter__page-mark` an invisible element to store the page reference to the books.  
`.chapter__meta` an element for anything that describe the book.  
`.chapter__title` an element for a chapter title that appears in the text.  
`.chapter__subtitle` an element for a chapter subtitle that appears in the text.  
`.chapter__item` an element for a numbered verse from the book. Each `.chapter__item` has `.chapter__item__number` as the first child.
`.chapter__pali` an element in Pali
