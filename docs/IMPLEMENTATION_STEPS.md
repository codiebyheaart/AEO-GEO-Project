# Implementation Steps: AEO + GEO

## Phase 1: Foundation (Days 1-3)

1. Choose one business use case:
   - Insurance
   - Healthcare
   - Ecommerce
   - B2B SaaS
2. Define target audience and top 20 user questions.
3. Create baseline content set:
   - 5 FAQ pages
   - 3 long-form guides
   - 5 short answer snippets (40-60 words)
4. Track all baseline metrics in templates/experiment-tracker.csv.

## Phase 2: AEO Project (Week 1)

1. Build question-first page structures:
   - H2 as question
   - Direct answer in first 1-2 lines
   - Follow with details and examples
2. Add structured data where relevant:
   - FAQ schema
   - HowTo schema
   - Organization schema
3. Optimize for concise answers:
   - 40-60 word summary
   - 120-180 word expanded answer
4. Test query coverage:
   - Who, What, Why, How, Cost, Eligibility, Timeline
5. Run weekly tests:
   - Check if answers are surfaced in snippets/answer blocks
   - Record rank movement and snippet appearance rate

## Phase 3: GEO Project (Week 2)

1. Build entity-rich content:
   - Mention brand, product, audience, location, domain entities clearly
2. Strengthen citation quality:
   - Add references to trusted sources
   - Add original data points when possible
3. Improve semantic coverage:
   - Include synonyms and related concepts
   - Add context windows (problem, cause, solution, tradeoffs)
4. Optimize for LLM retrieval:
   - Clear section labels
   - Fact tables
   - Precise definitions
5. Run prompt tests on AI engines:
   - Use fixed prompt sets from templates/test-case-template.md
   - Measure mention rate, citation rate, and answer accuracy

## Phase 4: Comparison Testing (Week 3)

1. Select 10 identical test queries.
2. Run each query across selected engines/tools.
3. Score each result (1-5):
   - Relevance
   - Accuracy
   - Completeness
   - Brand visibility
4. Compare AEO-optimized vs GEO-optimized pages.
5. Document wins, losses, and hypothesis.

## Phase 5: Real-World Pilot (Week 4)

1. Publish top-performing AEO and GEO assets.
2. Track 14-day performance trend.
3. Identify content blocks with best lift.
4. Create final recommendations:
   - Keep doing
   - Stop doing
   - Scale next

## Suggested Weekly Cadence

- Monday: Plan tests and create variants
- Tuesday: Publish/submit updates
- Wednesday: Run search and AI prompt checks
- Thursday: Analyze metrics and logs
- Friday: Publish weekly report and next actions
