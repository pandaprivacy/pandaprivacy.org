---
title: How to Use PANDA
description: an example for service providers
permalink: /how
---

## {{page.title}}

This page offers a short guide to using PANDA, from the point of view of an online service provider.  This isn't the only way or the only "right" way to use PANDA, but it's a good way to help clarify what PANDA is for and how it can fit into the real world.

***If you need legal advice for yourself or your company, don't follow this guide blindly.  Find a lawyer.  A good one will ask you good questions, to understand whether and how PANDA can work for you.***

Most online service providers take pains to _avoid_ mentioning their terms of service, privacy policies, and other legal or policy terms.  They have their reasons: those terms are nearly always fairly bad for users, and good for the provider.

PANDA is different.  Fundamentally, PANDA helps you differentiate your service by putting the law behind your commitment to protect users' personal information.  If users don't _see_ this commitment, they can't give you credit for it.

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
      I agree to
      <a href="{{site.url}}/versions/1.0.0" target="_blank" title="The Privacy Assuring Nondisclosure Agreement version 1.0.0">PANDA 1.0.0</a>
      for use of my personal information only to:
    </label>
  </p>
  <ul>
    <li>provide me the service</li>
    <li>keep the service working, efficient, safe, and secure for me and others</li>
  </ul>
  <button type="submit">Register</button>
</blockquote>

The server that responds to this form should keep a record of when the form was submitted and send a confirmation message that mentions PANDA 1.0.0 and the purposes, perhaps as part a new-user welcome e-mail.
