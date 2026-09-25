# Hi, I'm Alfie Catlow 👋

I'm learning Python and enjoy building small projects with HTML, JavaScript, and other technologies. I live in the UK and I'm interested in computers, Apple, coding, and Marvel Rivals.

## A tiny automatic maze game

This is a small, unbranded animation. You do not control it: the runner finds its way through each level automatically and always reaches the finish. Reloading the profile starts the animation from level 1 again.

<svg width="700" height="300" viewBox="0 0 700 300" role="img" aria-label="An automatic maze runner completing three levels">
  <rect width="700" height="300" rx="12" fill="#ffffff" stroke="#000000" stroke-width="2"/>
  <text x="24" y="34" font-family="Arial, sans-serif" font-size="20" font-weight="bold" fill="#000000">Automatic Maze Runner</text>
  <text x="24" y="58" font-family="Arial, sans-serif" font-size="13" fill="#444444">It finds the finish by itself</text>

  <g transform="translate(24 78)">
    <rect width="652" height="86" fill="#f4f4f4" stroke="#000000"/>
    <path d="M20 20H110V66H190V20H280V66H370V20H460V66H550V20H632 M20 66H65V34H150V66H235V34H325V66H410V34H500V66H632" fill="none" stroke="#000000" stroke-width="6"/>
    <circle r="8" fill="#000000">
      <animateMotion dur="4s" repeatCount="1" fill="freeze" path="M20,20 H110 V66 H190 V20 H280 V66 H370 V20 H460 V66 H550 V20 H632"/>
      <animate attributeName="fill" values="#000000;#000000;#16803c" keyTimes="0;.9;1" dur="4s" fill="freeze"/>
    </circle>
    <text x="20" y="82" font-family="Arial, sans-serif" font-size="11" fill="#444444">Level 1</text>
    <text x="615" y="82" font-family="Arial, sans-serif" font-size="11" text-anchor="end" fill="#16803c">FINISH</text>
  </g>

  <g transform="translate(24 178)">
    <rect width="652" height="86" fill="#f4f4f4" stroke="#000000"/>
    <path d="M20 66H95V20H180V66H265V20H350V66H435V20H520V66H632 M20 20H55V48H140V20H225V48H310V20H395V48H480V20H632" fill="none" stroke="#000000" stroke-width="6"/>
    <circle r="8" fill="#000000">
      <animateMotion begin="4s" dur="4s" repeatCount="1" fill="freeze" path="M20,66 H95 V20 H180 V66 H265 V20 H350 V66 H435 V20 H520 V66 H632"/>
      <animate attributeName="fill" begin="4s" values="#000000;#000000;#16803c" keyTimes="0;.9;1" dur="4s" fill="freeze"/>
    </circle>
    <text x="20" y="82" font-family="Arial, sans-serif" font-size="11" fill="#444444">Level 2</text>
    <text x="615" y="82" font-family="Arial, sans-serif" font-size="11" text-anchor="end" fill="#16803c">FINISH</text>
  </g>

  <text x="350" y="289" font-family="Arial, sans-serif" font-size="13" text-anchor="middle" fill="#444444">Level 3 starts when the page is opened again</text>
</svg>

## Projects

- **[Incident Tracker](https://github.com/rdmilkshakelab/incident-tracker)** — a simple TV-friendly tracker for days without incidents.

## Contact

- Email: [alfernado@outlook.com](mailto:alfernado@outlook.com)
- GitHub: [@rdmilkshakelab](https://github.com/rdmilkshakelab)
