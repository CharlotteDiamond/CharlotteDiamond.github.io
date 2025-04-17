<div class="timeline">
  {% for item in site.data.timeline %}
  <div class="timeline-item">
    <div class="timeline-date">{{ item.date }}</div>
    <div class="timeline-bar"><div class="timeline-progress" style="width: {{ item.progress }}%;"></div></div>
    <div class="timeline-content">
      <h3>{{ item.title }}</h3>
      <p>{{ item.details }}</p>
    </div>
  </div>
  {% endfor %}
</div>