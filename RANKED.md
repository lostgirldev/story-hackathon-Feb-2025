**Ranking:**

1.  **[https://github.com/ellieli0630/ave-agent-story-protocol-ip-management](https://github.com/ellieli0630/ave-agent-story-protocol-ip-management)**

    *   **Reasoning:** This project appears to have the most comprehensive and correct implementation of Story Protocol features. It implements IP Asset Registration, attaching licenses, registering derivative IPs, using SPG, paying royalties, claiming revenue and dispute resolution. The code also uses SDK methods. Other positives are that it implements Javascript/Typescript and has clear comments.

2.  **[https://github.com/GabinFay/VoiceIP](https://github.com/GabinFay/VoiceIP)**

    *   **Reasoning:** This project comes in second because it implements IP Asset Registration, attaching licenses, license tokens, and SPG. Furthermore, this plugin seems to allow retrieving IP Asset Details as well as getting available licenses. This demonstrates a practical use case and makes the code of higher quality.

3.  **[https://github.com/SohamGhugare/sourcetrust](https://github.com/SohamGhugare/sourcetrust)**

    *   **Reasoning:** This implementation has all the positives that all the others implementations have but is missing license terms attachment.

4.  **[https://github.com/brainrotbot/agent-communication-client](https://github.com/davidbegin/brainrotbot)**

    *   **Reasoning:** This project implements IP Asset Registration, Derivative IP registration, attaching licenses, and minting / registering IP assets in one transaction. It is also has good logging with a defined logger and has well organized files, however, there is some code duplication, as well as missing error handling.

5.  **[https://github.com/kingbootoshi/agent-communication-client](https://github.com/kingbootoshi/agent-communication-client)**

    *   **Reasoning:** This codebase's strengths lie in IP Asset Registration, adhering to the metadata standard, attempting derivative IP registration, and attaching PIL terms. However, it falls short due to hardcoded values, reliance on a parent NFT, and incomplete derivative registration and license attachment. It's a decent start, but needs more robust implementation and error handling.

6.  **[https://github.com/hololabster/superagent_playarts](https://github.com/hololabster/superagent_playarts)**

    *   **Reasoning:** It implements IP Asset Registration using `@story-protocol/core-sdk`, attaches PIL terms, and uploads metadata to IPFS. The code, however, uses hardcoded values and lacks user customization for license terms and is missing License Tokens.

7.  **[https://github.com/Pulse-Ip-superAgentHack/frontend-app](https://github.com/Pulse-Ip-superAgentHack/frontend-app)**

    *   **Reasoning:** Implements IP Asset Registration, the Metadata Standard, and SPG.
    *The presence of hardcoded `txnHash` values undermines the implementation. This should be replaced with dynamically fetched transaction hashes or IP Asset IDs retrieved directly from the Story Protocol after successful registration.

8.  **[https://github.com/WeOwnAiAgents-Hackerhouse/StoryHackathon](https://github.com/WeOwnAiAgents-Hackerhouse/StoryHackathon)**

    *   **Reasoning:** The app has IP asset registration, licensing, license token minting, and dispute features. The implementation relies heavily on mocks and doesn't use Story Protocol contracts, as well as using SPG. It has inconsistent network usage and error handling.

9. **[https://github.com/laboratoire-laplace/derive](https://github.com/laboratoire-laplace/derive)**

    *   **Reasoning:** The Derive project implements IP asset registration using `storyClient.ipAsset.mintAndRegisterIp` and utilizes `uploadMetadataToIPFS` to store IP and NFT metadata. However, these metadata formats do not fully comply with the Story Protocol specification, and doesn't propperly follow the schema for IP Metadata.

10. **[https://github.com/royalnine/eliza/tree/story_hackathon](https://github.com/royalnine/eliza/tree/story_hackathon)**

    *   **Reasoning:** Integrates Story features in eliza framework.
