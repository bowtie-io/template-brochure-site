---
location: homepage
head:
  title: null
  subtitle: null
style:
  id: 'countdown'
  class: 'carousel slide'
  media:
    img:
      url_path:
      pattern: false
      parallax: false
      overlay: light
      blur: false
    video:
      url_path:
      type:
  tint_color: null
  font_color: '#000'
element:
  countdown:
    date_on: 2015-10-09
    complete: this is complete
cta:
  headline: null
  btnText: null
  btnType: null
  btnLink: null
  subtext: null
---


{% include widgets/countdown.html date=page.element.countdown.date_on complete=page.element.countdown.complete %}
