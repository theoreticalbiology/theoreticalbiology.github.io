---
title: "Calendar"
permalink: /calendar/
layout: default
---
<div class="calendar-embed">
<iframe src="https://calendar.google.com/calendar/embed?src=45b751cf91b799869137518a49e26a0c44684497c0700bd68e7bad026109d70b%40group.calendar.google.com&ctz=UTC&mode=AGENDA" 
  style="border: 0"
  frameborder="0" 
  scrolling="no">
  </iframe>
  </div>

/* Responsive Google Calendar embed */
.calendar-embed {
  width: 100%;
}

.calendar-embed iframe {
  width: 100%;
  height: 80vh;        /* scales with viewport */
  min-height: 600px;  /* prevents it being too short */
  border: 0;
}
