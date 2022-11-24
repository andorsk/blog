---
title: "Verifiable Credentials and the @context debate"
date: 2022-11-24T16:37:18+05:30
draft: true
tags: ["vc", "identity"]
---

Over the last month or so, there has been some [heated
debates](https://github.com/w3c/vc-data-model/issues/947) in the identity space
regarding whether the @context field in the verifiable credential should be
optional or not.

<!--more-->

With hundreds of comments back and forth, this one really hit the community hard.

At the heart of the issue, advocates that desired the @context field to be
required generally advocated that enforcing the `@context`, greater
interoperability would be enforced. Proponents argued that it adds various
infrastructure and developer overhead, and restricted semantic models to
JSON Linked Data (JSON-LD), which is one of many potential representations such
as JSON Schema.

The debate has ultimately been coined by Drummond Reed as the `Great Divide`
happening right now in the W3C VC world, with fundamentally the community
realizing you can't have a cake and eat it too.

Why this all matters?

This was one of the most vibrant and complete discourses in the identity
community I've seen since joining. One of the beautiful parts about this
conversation was that it was grounded in real world examples, with passionate
people ultimately trying to figure out what's the right way to make VC's happen
in the real world.

Some interesting things I'm going to look into after this:

- [MsgPack](https://msgpack.org/index.html)
- [CBOR](https://cbor.io/)
- [JOSE](https://jose.readthedocs.io/en/latest/)
