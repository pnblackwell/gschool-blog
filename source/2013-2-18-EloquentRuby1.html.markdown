---
title: EloquentRuby1
date: 2013-02-18
---

I thought I understood the basic rules of programming- or at least how a computer program interprets what I enter into it before reading the section on optional expressions in Chapter 2.  The fact that you can create a conditional (maybe until isn't quite a conditional) after you have the actual command changed the way about how computers assess code. The section started off with this line of code: 

  unless read @read_only
    @title = new_title
  end

and then it switched to:

  @title = new_title unless @read_only

This is not a big logical jump at all.  The ordering seemed weird, but based on the fact that Ruby tries to be incredibly readable and similar to spoken language, this sentence structure makes sense.  I've never even used an until, so it wasn't that unfamiliar to me.  But then something crazy happened.  I'm going to quote directly from the book here:

"You can also do similar things with both while:

  document.print_next_page while document.pages_available?

And until:

  document.print_next_page until document.printed?  
"

I am familiar with while loops and that was something that I imagine will throw me off in the future.  It seems counter-intuitive in programming.  Page 26 also had an example of defining a variable without an equal sign.  This also isn't necessarily foreign to me, but the way it was presented didn't make much sense to me and it took some thinking to grasp.  It was simplification that caused me to approach it as if it were more complex.  We went from the code:

  @first_name = '' unless @first_name

and then went to 

  @first_name ||=''

Reading Eloquent Ruby has been helpful because it is putting a lot of code into context.  I'm beginning to understand why certain things are written different than others.
