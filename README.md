# Белая Мгла — v239 FIRST LOAD

Изменено только ускорение первой загрузки:
- CSS каждой страницы очищен от правил и фоновых изображений, относящихся к другим страницам;
- текущая шапка страницы получает preload с высоким приоритетом;
- блоки ниже первого экрана используют content-visibility:auto и отрисовываются по мере прокрутки.

Тексты, дизайн, изображения, порядок блоков и Каньон не изменялись.

v240
- Mobile breakpoint widened from 820px to 980px so Android phones reporting wider CSS viewports do not receive the desktop sidebar.
- Sidebar is always off-canvas on mobile/tablet and opens only from the menu button.
- Mobile content uses the full viewport for a closer, larger reading scale.
- Snow/feather decorative effects are disabled on <=980px to reduce phone rendering load.
- No text/content/event changes; Canyon untouched.
