# llm_seek
seek for llm knowledges

# AI core issues

**article**: [Verification, The Key to AI](http://incompleteideas.net/IncIdeas/KeytoAI.html)

**summary**:

The article "Verification, The Key to AI" by Rich Sutton presents a fundamental principle for successful AI development: AI systems must be able to verify their own knowledge and functioning. Key points include:

1. Self-verification capability
    - AI systems need to assess whether they're working correctly without human intervention
    - Systems that can self-verify may also self-modify and improve
    - This reduces dependency on human maintenance and oversight
2. The Verification Principle
    - "An AI system can create and maintain knowledge only to the extent that it can verify that knowledge itself"
3. Success examples in search-based systems
    - Chess programs like Deep Blue can verify move choices through search trees
    - This is more effective than early rule-based approaches that required constant human maintenance
    - TD-Gammon's strength comes from assessing and improving its own scoring function
4. Current limitations
    - Many systems still rely on human-tuned evaluation functions
    - Action outcomes are often pre-programmed rather than learned/verified
    - Large knowledge bases (like CYC) depend on human construction and maintenance
    - Most systems cannot verify their own knowledge claims
5. Implications
    - Systems without self-verification remain brittle and limited
    - Scalability of AI systems depends on their ability to self-verify
    - Human-dependent verification limits system size to what humans can monitor
