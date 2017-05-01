---
layout: post
title: "What exactly is a Domain?"
---

I've been lucky enough to be part of a team which is growing rapidly
and is convinced that the best way of managing the complexity of our
system is applying Domain Driven Design practices.

This is the first time that the team has tried to apply DDD to
a project. This is true also for me, even though I'm one of the greatest
(and most annoying) supporters of the idea.

It stroked me as peculiar that one of the confusion that has arisen in the
whole process is particularly the word: *Domain*.

So, what exactly is a domain? In the [Big Blue Book] [DDD] a domain is:
>A sphere of knowledge, influence, or activity.

This is, in practice, the whole activity of the business. The problem that we're 
trying to solve with our efforts. For example, if you're
into the selling sausages business the whole domain could be:
* The Ordering System where users could buy the product.
* Inventory system.
* Priority System to know where to deliver first.
* Decision support systems which track data.
* ...

Now, this could be represented in a Context Map:

![image-title-here](/assets/img/what-exactly-is-a-domain/1.png)

On the other hand, it could be also though as one of the areas of it. In the
sausage example, any system which represents a part of the whole business but
only if we work on the perspective of this problem. For the whole, these are
subdomains. They don't represent all the processes of the organization just a
part of it.

When we're applying DDD we're working on a Domain problem which we model with
Domain Models and we do our best in representing the rules of the business with
the code we write.

In summary, a *Domain* depends on the perspective we're designing our system:
in the whole, the forest perspective, the domain is the whole business we're in.
If we're working on some subsystem, either fundamental or support for the business,
that will be our domain.

[DDD]: https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/ref=sr_1_1?ie=UTF8&qid=1493644523&sr=8-1&keywords=domain+driven+design "Domain Driven Design"
