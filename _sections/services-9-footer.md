---
location: services
head:
  title: null
  subtitle: null
style:
  id: contact
  class: 'alt'
  media:
    img:
      url_path: null
      pattern:
      parallax:
      overlay:
      blur: false
  tint_color: 'rgba(163,166,152,0.6)'
cta:
  headline: null
  btnText: null
  btnType: null
  btnLink: null
  subtext: null

---

<div class="col-sm-9">
    <h4 class="text-left">Contact Us</h4>
    {% include widgets/contact-form.html email="contact@example.com"%}
</div>


<div class="col-sm-3">
<h4 class="text-left">Connect</h4>
{% include social-links.html %}

<h4 class="text-left">Visit Us</h4>
{% include widgets/visit-us.html %}
</div>
