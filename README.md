# RAG evaluation checklist

A short checklist for testing a retrieval-augmented generation (RAG) system before launch. Maintained by Syntalix Consultancy. The full explanation is at https://www.syntalixconsultancy.com/blog/evaluating-rag-systems

## Before you build

- [ ] Collect 50 to 100 real user questions from support tickets, search logs or interviews
- [ ] Write the correct answer for each question
- [ ] Note the document and page that contain each answer
- [ ] Add 10 or more questions your documents cannot answer

## Retrieval

- [ ] For each question, check whether the correct passage appears in the top results
- [ ] Record the hit rate
- [ ] If it is low, review document cleaning, chunk size, search method and re-ranking

## Answers

- [ ] Faithfulness: every claim is supported by the retrieved passages
- [ ] Relevance: the answer addresses the question that was asked
- [ ] A person has read a sample of the answers

## Refusals

- [ ] On unanswerable questions, the system says the information is not available
- [ ] The system points to a person or another resource where it can

## After launch

- [ ] Rerun the full set after every change to documents, prompt, retrieval settings or model
- [ ] Review answers that users rated poorly
- [ ] Add useful real questions to the set


