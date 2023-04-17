# pistash
The Pictures Stash

Pistash is a service to aggregate pictures from various sources. Inspired by
booru boards, think of it as a way to store and consult pictures you enjoyed,
while also keeping track of a bunch of metadatas so you can easily search
through them.

## Planned features

- Direct import of a resource from an URL to an external service
- Monitoring your likes / collections from other services for automatic imports
- Tags system which should be as much as possible automatically filled when
  using imports
- Support for at least the following services for importing resources
    - Twitter
    - Pixiv
    - Gelbooru engine
    - Danbooru engine
- Ability to use img2txt Stable Diffusion AI to complete tags
- Personal collections system

## Rationale

I'm a passionate enthusiast of anime-style drawings and have been following a
plethora of artists across multiple websites. Trying to follow that many artists
and from different platforms comes with a bunch of challenges, mainly having to
go back and forth between different websites to make sure you don't miss
anything. This especially become tedious if you want to look back at drawings
you enjoyed, most platforms do not allow you to perform a search in your
collection of "liked" works. Also there is the case of a work or the whole
artist's profile being deleted, effectively making it impossible for you to see
the work again.

Over the years I have developped multiple tools to help me keep track with the
flow of works posted and trying to aggregate them, but I was still lacking the
possibility to easily look back at the works I previously enjoyed, with Pistash
I'm trying to fill this hole.