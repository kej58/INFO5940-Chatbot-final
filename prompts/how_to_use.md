# How to Use This RAG Prompt Engineering Project

## Getting Started

1. **Choose a Topic**: Start with one of the three topics provided:
   - Food Safety (`food_safety_prompts.md`)
   - Mental Health (`mental_health_prompts.md`)
   - Wearable Health Tech (`wearable_health_tech_prompts.md`)

2. **Select Prompt Variations**: Each topic file contains 7 different prompt variations, ranging from simple questions to complex comparative inquiries.

3. **Test with Perplexity.ai**: Copy each prompt and paste it into Perplexity.ai (or your preferred free RAG model).

4. **Run Multiple Tests**: For each prompt, run at least 3 tests at different times of day to check for consistency in the results.

5. **Verify Sources**: For each source cited by the RAG model:
   - Check if the source actually exists
   - Verify if the information attributed to the source is accurate
   - Note the publication date and authority level of the source

6. **Record Results**: Use the `results_template.md` to document the results for each prompt variation and test run. Create a new copy of this template for each test.

## Tips for Effective Testing

- **Run tests close together but also across different times**: Run some tests in sequence to minimize the impact of model updates, but also run tests at different times of day/week to check for consistency.
- **Be consistent with settings**: Use the same settings in Perplexity.ai for all tests within a topic.
- **Take screenshots and save full responses**: Capture screenshots and save the complete text of responses for thorough documentation.
- **Verify source credibility**: Check the authority level of sources (academic, governmental, news, blogs) and publication dates.
- **Test for reproducibility**: Run the same prompt multiple times to see if the RAG model consistently retrieves the same sources and provides similar answers.
- **Document contradictions**: Note any contradictory information within answers or between different runs of the same prompt.

## Analyzing Your Results

After testing multiple prompt variations, look for patterns in:

- Which prompt styles consistently retrieve higher-quality, more verifiable sources
- How adding context affects the relevance and accuracy of information
- Whether specificity improves or narrows results too much
- How comparative questions affect the breadth and depth of information
- Which prompts produce the most stable and consistent results across multiple test runs
- Which prompts lead to the most practically useful information for real-world applications
- Whether certain prompt structures consistently lead to more recent or authoritative sources

## Extending the Project

Feel free to create your own prompt variations based on what you learn. You might discover that certain techniques work particularly well with RAG models and can be applied to other topics of interest.

## Data Quality Assurance

### Source Verification Process
1. **Check Source Existence**: Verify that each cited source actually exists by searching for it online.
2. **Content Verification**: When possible, access the original source to confirm that the information attributed to it is accurate.
3. **Authority Assessment**: Evaluate the credibility of each source based on:
   - Author credentials
   - Publishing organization
   - Peer review status (for academic sources)
   - Citation count or impact factor (where applicable)

### Consistency Testing
1. **Same-Day Testing**: Run the same prompt 2-3 times within a short timeframe to check for immediate consistency.
2. **Different-Day Testing**: Run the same prompt on different days to check for temporal stability.
3. **Cross-User Testing**: If possible, have different people run the same prompt to see if user profiles affect results.

These verification steps will help ensure that your prompt engineering findings are based on reliable, consistent data rather than anomalous results.
