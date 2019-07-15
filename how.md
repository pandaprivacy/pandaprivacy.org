---
title: How to Use PANDA
description: an example for service providers
permalink: /how
---

## {{page.title}}

This page offers a short guide to using PANDA, from the point of view of an online service provider.  This isn't the only way or the only "right" way to use PANDA, but it's a good way to help clarify what PANDA is for and how it can fit into the real world.

***If you need legal advice for yourself or your company, don't follow this guide blindly.  Find a lawyer.  A good one will ask you good questions, to understand whether and how PANDA can work for you.***

Most online service providers take pains to _avoid_ mentioning their terms of service, privacy policies, and other legal or policy terms.  That makes sense.  Those terms are nearly always fairly bad for users, and good for the provider.

PANDA is different.  Fundamentally, PANDA is _good_ for users. If your service protects users' personal information, PANDA can be good for you, too.  By offering to agree to PANDA with users, you show that you're willing to put the law behind your commitment to protect personal information.  If users don't _see_ that assurance, they can't give you credit for it.

Consider a new kind of sign-up form:

<blockquote>
  <p>
    <label for="name">Name</label><br>
    <input name="text" type="name">
  </p>
  <p>
    <label for="email">E-Mail</label><br>
    <input name="email" type="email">
  </p>
  <p>
    <label for="password">Password</label><br>
    <input name="password" type="password">
  </p>
  <p>
    <input name="nda" type="checkbox">
    <label for="nda">
      I agree to the
      <a href="http://example.com">terms of service</a>,
      plus
      <a href="{{site.url}}/versions/1.0.0" target="_blank" title="The Privacy Assuring Nondisclosure Agreement version 1.0.0">PANDA 1.0.0</a>
      for use of my personal information to:
    </label>
  </p>
  <ul>
    <li><p>provide me the service</p></li>
    <li><p>keep the service working, efficient, safe, and secure for me and others</p></li>
  </ul>
  <button type="submit">Register</button>
</blockquote>

The server that responds to this form should keep a record of when the form was submitted and send a confirmation message that mentions PANDA 1.0.0 and the purposes, perhaps as part a new-user welcome e-mail.  That way both you and your new user have records of that agreement.
