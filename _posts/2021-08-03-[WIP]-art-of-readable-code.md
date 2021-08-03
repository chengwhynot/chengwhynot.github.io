---
title: sssss
date: 2021-08-03
category: coding habbits 
---

## Chapter 2 Summary

The single theme for this chapter is: pack information into your names. By this, we mean
that the reader can extract a lot of information just from reading the name.

Here are some specific tips we covered:
. Use specific words—for example, instead of Get, words like Fetch or Download might be
better, depending on the context.
. Avoid generic names like tmp and retval, unless there’s a specific reason to use them.
. Use concrete names that describe things in more detail—the name ServerCanStart() is vague compared to CanListenOnPort().
. Attach important details to variable names—for example, append _ms to a variable whose value is in milliseconds or prepend raw_ to an unprocessed variable that needs
escaping.
. Use longer names for larger scopes—don’t use cryptic one- or two-letter names for variables that span multiple screens; shorter names are better for variables that span only a few lines.
. Use capitalization, underscores, and so on in a meaningful way—for example, you can append “_” to class members to distinguish them from local variables.

## Chapter 3 Summary

The best names are ones that can’t be misconstrued—the person reading your code will understand it the way you meant it, and no other way. Unfortunately, a lot of English words are ambiguous when it comes to programming, such as filter, length, and limit.

Before you decide on a name, play devil’s advocate and imagine how your name might be misunderstood. The best names are resistant to misinterpretation.

When it comes to defining an upper or lower limit for a value, max_ and min_ are good prefixes to use. For inclusive ranges, first and last are good. For inclusive/exclusive ranges, begin and end are best because they’re the most idiomatic.

When naming a boolean, use words like is and has to make it clear that it’s a boolean. Avoid negated terms (e.g., disable_ssl).

Beware of users’ expectations about certain words. For example, users may expect get() or size() to be lightweight methods.
