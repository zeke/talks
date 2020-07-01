# Bridging systems and subcultures: a Swagger origin story

In 2011 I joined a startup called Wordnik. We dreamed of building the world's largest English dictionary. Like so many well-meaning startups, we didn't have a viable business model and we eventually ran out of money. But the open-source project we created lives on: that project was Swagger.

Swagger (now OpenAPI) is a machine-readable specification for documenting HTTP web services. It was created to bridge a gap, not just between our product's frontend and backend services, but between differing engineering subcultures at our company. Our tooling and language preferences differed, but we shared the common goal of building something fun and useful. We needed a language-agnostic way to describe our APIs, a kind of contract that could be co-authored by our frontend and backend teams. That contract became Swagger.

Nearly ten years later, Swagger's name has changed and the specification has matured, but OpenAPI still serves the same purpose: bridging gaps between systems, and between humans.

In this talk, I'll share some history about how Swagger was created, and why I named it Swagger! I'll also cover how we use OpenAPI and JSON Schema at GitHub today to render product documentation, generate API clients in multiple languages, and validate and test the internals of GitHub's APIs.

## Organizer Notes

Hi organizers!

I have spent my last year at GitHub working on docs.github.com, a new site powered in part by new OpenAPI schemas. That site happens to be launching tomorrow(!), July 1, but it's already quietly live now. You can check out the new OpenAPI-powered REST pages at https://docs.github.com/en/rest/reference

I would love to have an opportunity to finally tell my story about Swagger. Thanks for considering me!

Zeke