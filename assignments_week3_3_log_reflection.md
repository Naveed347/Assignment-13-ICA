# Audit Table, Transcript Excerpt, and Reflection

## 1. Audit Table (Review of AI Interpretation)
| Claim / Statement | Colour Code | How Checked | Verdict |
| :--- | :--- | :--- | :--- |
| "Sweetener D increased in price by 19.4% over the period." | **Green** | Recomputed from teaching data (`152.0` to `181.5`). | Accepted |
| "The price hikes were driven by increased export demand." | **Red** | Checked dataset columns; no trade or export data was provided. | Rejected |
| "Median is a safer metric than the mean when city-level prices are skewed." | **Amber** | Theoretical statistical concept explaining distribution shape. | Accepted (as explanation) |

---

## 2. Confused Classmate Transcript Excerpt
* **Classmate AI:** "I still don't get why my neighbor insists on using the median. The mean is the average of everything, so it must be the true typical price!"
* **Student:** "The mean is sensitive to extreme high or low prices (outliers). If one city has an abnormally high price spike, it pulls the mean up, making it higher than what most people actually pay."
* **Classmate AI:** "Ah, so the median is just the middle value so extreme prices don't distort it as much?"
* **Student:** "Exactly. When price distributions are skewed, the median gives a better representation of the central, typical consumer experience."
* **Classmate AI:** "Got it! That explains why the two neighbors kept arguing."

---

## 3. Reflection
In my first draft, I initially suggested that the price trends were a direct result of seasonal consumer demand surges. Upon auditing, I realized this statement went beyond the data allowed, as our dataset only contains raw prices across cities and dates without any volume, weather, or economic driver variables. Moving forward, I will ensure causal claims are strictly kept out unless supported by explicit econometric variables.
