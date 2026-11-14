# Part B: Requirements

Each requirement has one idea and can be tested. "Condition label" means one of four values: **Like New**, **Good**, **Fair** or **Poor**.

## B1. Functional Requirements

| ID | Requirement | How to test |
| :--- | :--- | :--- |
| FR1 | The system shall suggest an ad title from the photos the seller uploads. | Upload 3 photos of a phone. A title appears. |
| FR2 | The system shall suggest an ad category from the photos the seller uploads. | Upload 3 photos of a chair. A furniture category appears. |
| FR3 | The system shall suggest a condition label (Like New, Good, Fair or Poor) from the photos. | Upload photos of a scratched item. A label appears. |
| FR4 | The system shall let the seller edit every suggested value before the ad is published. | Change a suggested title and publish. The new title is saved. |
| FR5 | The system shall show a price range based on prices of similar ads in the same category. | Enter a used laptop. A low and a high price appear. |
| FR6 | The system shall warn the seller when a photo is smaller than 800 x 600 pixels. | Upload a 400 x 300 photo. A warning appears. |
| FR7 | The system shall let an AI agent answer a buyer question when the seller is offline, using only the details in the ad. | Ask "Is the item still new?" while the seller is offline. The agent replies from the ad text. |
| FR8 | The system shall pass a buyer question to the seller when the agent cannot answer it from the ad details. | Ask a question that is not in the ad. The seller gets the question. |
| FR9 | The system shall let buyers filter search results by condition label. | Choose "Like New". Only Like New ads show. |

## B2. Non-Functional Requirements

| ID | Type | Requirement |
| :--- | :--- | :--- |
| NFR1 | Performance | The system shall show title, category and condition suggestions within 3 seconds for up to 5 photos, in at least 90% of tries. |
| NFR2 | Usability | A seller shall need 4 clicks or fewer to publish an ad after the photos are uploaded (Nielsen, 2020). |
| NFR3 | Transparency | Every message sent by the AI agent shall show an "AI Assistant" badge, in 100% of messages. |
| NFR4 | Security and privacy | Photos shall be sent over HTTPS (TLS 1.2 or higher), and the AI service shall delete the photos within 24 hours. |
| NFR5 | Reliability | If the AI service fails, the seller shall still be able to publish the ad with the normal manual form. |
| NFR6 | Accuracy | The category suggestion shall be correct for at least 85% of photos in a test set of 100 ads. |

## Reference

Nielsen, J. (2020). *10 usability heuristics for user interface design*. Nielsen Norman Group. https://www.nngroup.com/articles/ten-usability-heuristics/
