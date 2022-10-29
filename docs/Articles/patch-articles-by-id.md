---
id: patch-articles-by-id
title: PATCH /api/articles/:article_id
sidebar_position: 4
---

This will update an article's vote count by what the user passes in.

## Request Body

Accepts the following keys:

- article: Number
- inc_votes: Number


```json
{
  "article_id": 37,
  "inc_votes": 32
}
```

## Example Response

If a successful patch request is mad to the specified comment, then the votes property for that comment will increase by the specified amount.

```json
{
	"article_id": 37,
	"title": "Thank you Christian and Mitch",
	"topic": "coding",
	"author": "grumpy19",
	"body": "You two have been the most amazing mentors that we could have ever asked for. On October 28th 2022 for the Northcoders August 30th Cohort, we have had to bid our two favourite mentors goodbye. However, goodbyes are only temporary and we will see you both again soon. All of the best for the future cohorts and more you two!",
	"created_at": "2022-10-29T16:01:34.834Z",
	"votes": 32
}
```