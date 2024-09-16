---
layout: home
pagination:
  enabled: true
---

<div class="channel-info">
  <div class="logo">
    <img src="{{ site.telegram_channel.logo | relative_url }}" alt="Logo">
  </div>
  <div class="stats">
    Telegram Channel: <a href="https://t.me/{{ site.telegram_channel.id }}" target="_blank">@{{ site.telegram_channel.id }}</a><br>
    Subscribers: {{ site.telegram_channel.num_of_subscribers }}<br>
    Posts: {{ site.memblocks | size }}<br>
    Created: {{ site.telegram_channel.created_at | date: "%B %d, %Y" }}
  </div>
</div>

---
{: .divider}
