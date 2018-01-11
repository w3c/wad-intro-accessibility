---
title: Introduction to Web Accessibility
permalink: /fundamentals/accessibility-intro/
redirect_from: /
layout: default
# date: 2016-05-08
# people:
#   editorslabel: "Editor"
#   editors:
#     - name: Kevin White
#       url: https://www.w3.org/People/kevin/
#     - name: Shadi Abou-Zahra
#       url: https://www.w3.org/People/Shadi/
#   contributors:
#     - name: Judy Brewer
#       url: https://www.w3.org/People/Brewer/
#     - name: Shawn Lawton Henry
#       url: https://www.w3.org/People/Shawn/
# support:
#   - name: WAI-ACT Project, a project of the European Commission IST Programme
#     url: http://www.w3.org/WAI/ACT/
---

{::nomarkdown}
{% include box.html type="start" class="simple" %}
{:/}
<h2>Summary</h2>
<p>Properly designed and coded websites and tools can be used by people with disabilities. However, currently many sites and tools are developed with accessibility barriers that make it difficult or impossible for some people to use them. This page explains more about:</p>
<ul>
  <li><a href="#intro">Accessibility in Context</a></li>
  <li><a href="#i-what">What is Web Accessibility</a></li>
  <li><a href="#important">Accessibility is Important for Individuals, Organizations, Society</a></li>
  <li><a href="#making">Making the Web Accessible</a></li>
  <li><a href="#evaluate">Evaluating Accessibility</a></li>
  <li><a href="#more-info"> More Information</a></li>
</ul>
<p>You might also be interested in a 4-minute <a href="https://www.w3.org/WAI/videos/standards-and-benefits.html">Video Introduction to Web Accessibility and W3C Standards</a>.</p>
{::nomarkdown}
{% include box.html type="end" %}
{:/}
<h2 id="intro">Accessibility in Context</h2>
<blockquote>
  <p><q>The power of the Web is in its universality.<br />
    Access by everyone regardless of disability is an essential aspect.</q><br />
    <cite>&mdash; Tim Berners-Lee, W3C Director and inventor of the World Wide Web</cite></p>
</blockquote>
<p>The Web is fundamentally designed to work for all people, whatever their hardware, software, language,  location, or  ability. When the Web meets this goal, it is accessible to people with a diverse range of hearing, movement, sight, and cognitive ability.</p>
<p>Thus <strong>the impact of disability is radically changed on the Web because the Web removes barriers</strong> to communication and interaction that many people face in the physical world. However, when websites,  applications, technologies, or  tools are badly designed, they can create barriers that exclude people from using the Web.</p>
<p style="background-color: #f1f7fb"><strong>Accessibility is essential for developers and organizations that want to create high quality websites and web tools, and not exclude people from using their products and services.</strong></p>
<h2 id="i-what">What is Web Accessibility</h2>
<p> Web accessibility means that people with disabilities can use the Web.
  More specifically, it means  people with disabilities can:</p>
<ul>
  <li>perceive, understand, navigate, and interact with the Web</li>
  <li>contribute to the Web</li>
</ul>
<p>Web accessibility encompasses all disabilities that  affect access to the Web, including:</p>
<ul>
  <li>auditory</li>
  <li>cognitive</li>
  <li>neurological</li>
  <li>physical</li>
  <li>speech</li>
  <li>visual </li>
</ul>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}<strong><em>More info:</em></strong> When you want to learn more about how different
  disabilities affect Web use, and read about scenarios of people with
  disabilities using the Web, see <a href="http://www.w3.org/WAI/intro/people-use-web/Overview.html">How People with Disabilities Use the Web</a>.{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p>Web accessibility  also <strong>benefits</strong> people <em>without</em> disabilities, for example:</p>
<ul>
  <li>people using mobile phones, smart watches, digital TVs, etc.</li>
  <li>older people with changing abilities due to ageing</li>
  <li>people with "temporary disabilities" such as a broken arm</li>
  <li>people is an environment where they cannot listen to audio</li>
  <li>people using a slow Internet connection, or how have limited or expensive bandwidth</li>
</ul>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}<strong><em>More info:</em></strong> If you want  specific examples of benefits for others with  WCAG to back it up, see <a href="https://www.w3.org/WAI/bcase/soc#groups">Web Accessibility Benefits People With and Without Disabilities</a>.{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p>To see a 7-minute video with examples of how accessibility is essential for people with disabilities and useful for everyone in a variety of situations, check out: <a href="https://www.youtube.com/watch?v=3f31oufqFSM">Web Accessibility Perspectives Video</a>.</p>
{% include excol.html type="start" id="examples" %}
<h3>3 Examples of Web Accessibility</h3>
{% include excol.html type="middle" %}
<h4>Alternative Text for Images</h4>
<span class="example-alt"><img src="http://www.w3.org/WAI/intro/alt-logo.png" alt="image of logo; HTML markup img alt='Web Accessibility Initiative logo'" /></span>
<p>Images should include <em><a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv.html">equivalent alternative text</a></em> (alt text) in the markup/code.</p>
<p>If alt text isn't provided for images, the image information is inaccessible, for example, to people who cannot see and use a screen reader that reads aloud the information on a page, including the alt text for the visual image.</p>
<p>When equivalent alt text is provided, the information is available to people who are blind, as well as to people who turn off images (for example,  in  areas with expensive or low bandwidth). It's also available to technologies that cannot see images, such as search engines.</p>
<h4>Keyboard Input</h4>
<span class="example-di"><img src="https://www.w3.org/WAI/intro/no-mouse.png" width="67" height="45" alt="mouse crossed out" /></span>
<p class="di">Some people cannot use a mouse, including many older users with limited fine motor control. An accessible website does not rely on the mouse; it makes <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation.html">all functionality available from a keyboard</a>. Then people with disabilities can use <a href="http://www.w3.org/WAI/users/involving#at">assistive technologies</a> that mimic the keyboard, such as speech input.</p>
<h4>Transcripts for Audio</h4>
<span class="example-transcript"><a href="http://www.w3.org/WAI/highlights/200606wcag2interview.html"><img src="http://www.w3.org/WAI/intro/transcript.png" width="251" height="254" alt="example transcript" /></a></span>
<p>Just as images aren't available to people who can't see, audio files aren't available to people who can't hear. Providing a text transcript makes the audio information accessible to people who are deaf or hard of hearing, as well as to search engines and other technologies that can't hear.</p>
<p>It's easy and relatively inexpensive for websites to provide transcripts. There are also <a href="http://www.uiaccess.com/transcripts/transcript_services.html">transcription services</a> that create text transcripts in HTML format.</p>
{% include excol.html type="end" %}
<h2 id="important"> Accessibility is Important for Individuals, Organizations, Society</h2>
<p>The Web is an increasingly important resource in many aspects of life: education, employment, government, commerce, health care, recreation, and more. It is essential that the Web be accessible in order to provide <strong>equal access</strong> and <strong>equal opportunity</strong> to people with diverse abilities. An accessible Web can also help people with disabilities more actively participate  in society. Access to information and communications technologies, including the Web, is defined as <strong>a basic human right</strong> in the United Nations Convention on the Rights of Persons with Disabilities.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}<strong><em>Link:</em></strong> <a href="http://www.un.org/disabilities/convention/conventionfull.shtml">UN Convention on the Rights of Persons with Disabilities</a>{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p>The Web offers the possibility of <strong>unprecedented access to information and interaction</strong> for many people with disabilities. That is, the  accessibility barriers to print, audio, and visual media can be much more easily overcome through web technologies.</p>
<p><strong>Accessibility supports social inclusion</strong> for people with disabilities as well as others, such as older people, people in rural areas, and people in developing countries.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}<strong><em>More info:</em></strong> Details on business benefits are in <a href="/WAI/bcase/Overview">Developing a Web Accessibility Business Case for Your Organization</a>.<br/>
<br/>
Guidance on figuring out legal requirements is in <a href="https://www.w3.org/WAI/bcase/pol">Legal and Policy Factors</a>.{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p><strong>There is also a strong business case for accessibility.</strong> Accessibility overlaps with other best practices such as mobile web design, device independence, multi-modal interaction, usability, design for older users, and search engine optimization (SEO). Accessible websites can have better search results, reduced maintenance costs,  increased audience reach, and demonstrate  corporate social responsibility (CSR).</p>
<p>Web accessibility is <strong>required by law </strong>in some cases.</p>
<h2 id="making">Making the Web Accessible</h2>
<p>Web accessibility depends on several components working together, including web technologies,  browsers,  tools, and websites.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}<strong><em>More info:</em></strong> To learn more about the different roles and accessibility standards, see <a href="components.php">Essential Components of
  Web Accessibility</a>.{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p>The W3C Web Accessibility Initiative (<a href="../about-links">WAI</a>) develops guidelines, techniques,  technical specifications, and supporting resources that describe accessibility solutions. These    are considered the international standard for web accessibility; for example, the Web Content Accessibility Guidelines (WCAG) 2.0 is also an <abbr title="International Organization for Standardization">ISO</abbr> standard: ISO/<abbr title="International Electrotechnical Commission">IEC</abbr> 40500.</p>
<h3 id="specific">Making Your Website Accessible</h3>
<p>Most of the basics of accessibility are fairly easy to implement.  However, if you are new to accessibility, it takes some time and effort to learn the common issues and solutions.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple" %}
{:/}
<p><strong><em>More info</em></strong>: Here are places to start understanding website accessibility issues:</p>
<ul>
  <li><a href="https://www.w3.org/WAI/intro/people-use-web/principles">Accessibility Principles</a> &mdash; introduces accessibility requirements and international standards.</li>
  <li><a href="https://www.w3.org/WAI/eval/preliminary">Easy Checks - A First Review</a> &mdash; helps you start testing the accessibility of a web page and understand some common accessibility barriers.</li>
  <li><a href="https://www.w3.org/WAI/gettingstarted/tips/">Tips for Getting Started</a> &mdash; provides some basic considerations for designing, writing, and developing.</li>
</ul>
{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p>Some accessibility barriers are more complicated to avoid and the solutions take more development time and effort.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple" %}
{:/}
<p><strong><em>More info</em></strong>: When you're ready to go deeper, you'll probably use resources such as:</p>
<ul>
  <li><a href="http://www.w3.org/WAI/WCAG20/quickref/">How to Meet WCAG 2.0 (Quick Reference)</a></li>
  <li><a href="https://www.w3.org/WAI/tutorials/">Web Accessibility Tutorials</a></li>
</ul>
{::nomarkdown}
{% include box.html type="end" %}
{:/}
<p>It is most efficient and effective to incorporate accessibility from the beginning of projects and throughout organizations.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}
<p><strong><em>More info</em></strong>: For guidance, see <a href="https://www.w3.org/WAI/impl/">Planning and Managing Web Accessibility</a>.</p>
{::nomarkdown}
{% include box.html type="end" %}
{:/}
<h2 id="evaluate">Evaluating  Accessibility</h2>
<p>When developing or redesigning a website, evaluate accessibility early and throughout the development process to identify accessibility problems early, when it is easier to address them. Simple techniques such as changing settings in a  browser can  determine if a web page meets some accessibility guidelines. A comprehensive evaluation to determine if a site  meets all accessibility guidelines  is much more complex.</p>
<p>There are evaluation  tools that  help with evaluation. However, no tool alone can determine if a site meets accessibility guidelines. Knowledgeable <strong>human evaluation is required</strong> to determine if a site is accessible.</p>
{::nomarkdown}
{% include box.html type="start" title="More Info" class="simple right" %}
{:/}
<em><strong>More info:</strong></em> Resources to help with accessibility evaluation are described in <a href="/WAI/eval/Overview.html">Evaluating Web Sites for
	Accessibility</a>.{::nomarkdown}
{% include box.html type="end" %}
{:/}
<h2 id="more-info">For More Information</h2>
<p>W3C WAI provides a wide range of resources on different aspects of web accessibility <a href="https://www.w3.org/WAI/guid-tech">standards</a>, <a href="https://www.w3.org/WAI/train">education</a>, <a href="https://www.w3.org/WAI/eval">testing/evaluation</a>, <a href="https://www.w3.org/WAI/managing">project management, and policy</a>. We encourage you to explore thsis website, or look through the <a href="http://www.w3.org/WAI/Resources/">WAI Resources</a> list.</p>
