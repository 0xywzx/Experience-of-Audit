## Audit Type
Audit Firm

## Project Category
ERC20

## Score

| Quality | CostPerformance | Communication | Speed |
| --- | --- | --- | --- |
| 3 | 4 | 5 | 5 |
| Quality of the Report | Understanding of the Audit Subject | Flexibility | Willingness to Re-audit |
| 3 | 4 | 4 | 4 |

## **GitHub Repository (Code)**

https://github.com/jcam1/JPYCv2

## * **Audit Cost Details**

- Total cost ~~or Per Line~~：$18K USD
- Payment method：USDC on Ethereum mainnet
- Payment Terms：Before the audit begins. The audit process starts after the payment is completed.

---

## * **Reason for Choosing the Audit Firm**

We chose our audit firm based on budgetary constraints and time considerations.

While we recognize that the quality of an audit is often correlated with its cost, our service is still in its growth phase, making it challenging to allocate a large budget for auditing. Therefore, we chose an audit firm that offers good value for money.

Additionally,  it was crucial to select a firm that could respond promptly because the product release was fixed and we had to finish the audit until that time.

## **Communication with the auditors**

For this audit, we forked the code from USDC, so there was no need for us to provide detailed explanations about the code. As a result, the audit was conducted solely through text-based communication.

The auditors were quick to respond, allowing the audit process to proceed smoothly.

We used a Telegram group for communication and exchanged information there.

## * **Cost performance and audit quality**

Since we utilized code forked from USDC, the auditors were able to quickly grasp the project.

As a result, we received a speedy audit at an affordable price.

Furthermore, we received detailed explanations for any issues raised, and they also checked specific changes and areas we particularly wanted them to focus on during the audit.

We were satisfied with both the cost and quality of the audit.

## * **Advice for those who are considering an audit**

I recommend this audit firm for those who are confident in their code but want to request an audit just to be on the safe side, since they offer reasonable prices and quick responses. However, as your service expands and grows, I strongly advise undergoing additional audits in the future.

If there are specific parts of the code or concerns you want the audit to focus on, clearly communicating these requests could yield detailed feedback on those points. Therefore, if you have particular items or concerns you want to be addressed during the audit, I suggest listing them out in advance.

---

## **Audit Schedule**

The audit schedule was finalized after the completion of the audit fee payment. Additionally, we were allowed to make changes to the code until the start of the audit.

The overall audit duration was approximately one week, and it proceeded as follows:

- Two days after the audit began, we received an update on the interim progress.
- One week from the start of the audit, we received the First report. There were no particular items that needed correction in this report, so we communicated our perspective on the pointed-out issues.
- Five days after receiving the First report, we received the Final report, marking the completion of the audit.

If there were items that needed correction, the auditors would re-check the code after the necessary modifications. Moreover, during the audit, we identified and corrected some codes that weren't pointed out, and they checked those changes.

---

## **What We Proactively Prepared for the Audit**

We focused intently on three main areas: "Documentation," "Test Code," and "Team Management."

Firstly, we enriched our documentation. We provided detailed explanations of the contract architecture, overviews of each contract, in-depth descriptions of crucial functions, and the rationale behind our technical choices. This was done to ensure that anyone reviewing the documentation could fully grasp our product.

Regarding test code, we listed all test cases and wrote the test code to achieve 100% coverage. While auditors might not delve into the specifics of the test code, we believed it was crucial to do everything possible before the audit to enhance the contract's quality and, by extension, the audit's quality.

In terms of team management, we documented all internal meetings and research related to the audit, ensuring transparency in every decision-making process. Additionally, we made efforts to ensure that team members involved in the audit had a deep understanding of the code, equipping them to answer any questions that might arise.

## **Tools and websites that you used for audit**

- Code Analysis Tool
    - [Mythril](https://github.com/ConsenSys/mythril)
- Contract Checklist
    - https://github.com/sushiswap/bentobox/blob/master/documentation/checks.txt
    - https://github.com/Rari-Capital/security-checklist
- Things to be cautious of when writing Solidity:
    - https://github.com/sigp/solidity-security-blog
    - https://swcregistry.io/
    - https://consensys.github.io/smart-contract-best-practices/
- Hacking Case Studies
    - https://github.com/ethereumbook/ethereumbook/blob/develop/09smart-contracts-security.asciidoc

## **What did you learn from the audit report**

There were no particularly significant issues raised during the audit.

However, roles and permissions, especially those related to the "owner" function in smart contracts, are frequently pointed out by auditors.

Therefore, we recommend documenting in advance details like what powers each role holds, when it is executed, and how it is managed (e.g., Multisig, cold wallet).