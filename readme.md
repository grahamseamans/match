# AI-Powered Matching Concept

## Overview

This document proposes a matching system where you interact exclusively through a simple text interface with an LLM. Users will never view or edit their own, or any user's profile, or communicate directly with other users. Instead, the LLM handles everything in the background—building and editing your profile through conversation, finding matches, and asking users follow-up questions. Everyone can be honest search over a much larger search space.

## How It Works

### 1. User Profile Creation

* When a user first logs in, an AI assistant chats with them to build a profile.
* Users are be fully transparent because no user sees other user data directly.

### 2. AI-Powered Searching and Matching

* Behind the scenes, llm's use these profiles to find potential matches.
* The AI can perform different types of searches:

  * **Semantic Search:** Understanding nuanced meanings and synonyms (e.g., recognizing "outdoorsy" as similar to "hiking").
  * **Classic Fuzzy Search:** Simple, direct text matching based on user details.
  * **Location and other specialized searches:** Tools specifically tailored to find matches based on proximity, lifestyle, or specific preferences.
* The AI can even create its own specialized search tools to find better matches over time.

### 3. Iterative Improvement through Follow-Up Questions

* When the AI identifies potential matches, it comes back to users with follow-up questions:

  * "Are you interested in this person? Why or why not?"
  * "This user had a question about something important to them. Could you clarify your stance or details on that?"
* The user's responses allow the AI to continuously refine and improve the user's profile and future searches.

## Privacy and Honesty First

* Crucially, **no human sees another user's raw profile data directly**. Users interact exclusively with the AI. If there's a match, The ai will share their contact info with eachother, and they can connect offsite.

## Generalized Matching System

* While for dating, this exact system can works just as well well for friends, professional, teammates, or any kind of compatiblility / search problems.
