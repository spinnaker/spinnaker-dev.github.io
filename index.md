---
layout: home
spinnaker_row:
  title: Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.
  excerpt: "Created at Netflix, it has been battle-tested in production by hundreds of teams over millions of deployments. It combines a powerful and flexible pipeline management system with integrations to the major cloud providers."
  image_path: assets/images/spinnaker-logo-inline.svg
  alt: "Spinnaker Logo"
spinnaker_dev_row:
  title: Welcome to the Spinnaker Developers' site.
  excerpt: "You can find documentation for operating and using Spinnaker, and
  for OSS Spinnaker community involvement,
  on [spinnaker.io](https://www.spinnaker.io)."

---

<div class="spin_header">
  <img class="spin_header__swoosh" src="{{ "assets/images/top-right-swoosh.svg" | absolute_url }}" alt="Spinnaker Swoosh"/>
  <div class="spin_header__inner_wrap">

    {% include masthead.html %}

    <div class="spin_header__text">
      <h1>Spinnaker Developers' Resources</h1>
      <h2>Continuous delivery for enterprise</h2>
    </div>
    <ul class="spin_call_to_action">
      <li><a href="/reference/api/">GATE API REFERENCE</a></li>
      <li><a href="https://www.spinnaker.io">spinnaker.io</a></li>
    </ul>
  </div>
</div>

<div class="spin_header__push_down">
{% include splash_feature_row id="spinnaker_dev_row" type="left" %}
{% include splash_feature_row id="spinnaker_row" type="right" %}
</div>
