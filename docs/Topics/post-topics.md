---
id: post-topics
title: POST /api/items
sidebar_position: 2
---

This will post a new topic that's created by the user upon a succesful post request. 

## Request Body

Accepts the following keys:

- slug: String **required** 
- description: String **required**

The `slug` property will reference the topic's name and the description will be the description that the topic has.

```json
{
    "slug": "Languages",
    "description": "An entire topic for all of those amazing polyglots out there."
}
```

## Example Response

```json
{
    "slug": "Languages",
    "description": "An entire topic for all of those amazing polyglots out there."
}
```