---
# Display name
title: Sanoop Mallissery

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: |
  Lecturer

  School of Information Technology

organizations: 
  - name: 
      Monash University Malaysia
    url: https://www.monash.edu.my

# Status emoji
status:
  icon: 💻 

# Short bio (displayed in user profile at end of posts)
bio: My research interests include advancing dependable systems security, privacy preservation, and cybersecurity in Operational Technology (OT) and Industrial Control Systems (ICS).

#interests:
#- Artificial Intelligence
#- Computational Linguistics
#- Information Retrieval

#education:
#  courses:
#  - course: PhD in Artificial Intelligence
#    institution: Stanford University
#    year: 2012
#  - course: MEng in Artificial Intelligence
#    institution: Massachusetts Institute of Technology
#    year: 2009
#  - course: BSc in Artificial Intelligence
#    institution: Massachusetts Institute of Technology
#    year: 2008

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'about/#contact' # For a direct email link, use "mailto:test@example.org".
  - icon: github
    icon_pack: fab
    link: https://github.com/git4san
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/sanoop-mallissery-ph-d-711616a2/
  - icon: google-scholar
    icon_pack: ai  # Custom pack for academic icons if available; otherwise use a text label/icon
    link: https://scholar.google.co.in/citations?user=2SUBIBkAAAAJ&hl=en
  - icon: orcid
    icon_pack: ai
    link: https://orcid.org/0000-0003-3472-2717

# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
#email: ""
---


<div class="justified-text">
  Sanoop Mallissery is a Lecturer at the School of Information Technology, Monash University Malaysia. He holds a Ph.D. in Computer Science from National Yang Ming Chiao Tung University (NYCU) in Taiwan, where he specializes in advanced cybersecurity research. He earned his Bachelor's degree in Information Technology and a Master's in Cyber Security, building a solid foundation.
</div>

<a id="toggleLink" href="#" onclick="toggleContent()" style="display: block; margin-top: 10px;">Read more</a>

<div class="justified-text" id="extraContent" style="display: none;">
    <p>Sanoop's professional experience includes a role as a threat researcher at TxOne Networks in Taiwan, where he contributed to innovative solutions in the Threat Research department. Before that, he spent four years as a cybersecurity engineer at the Industrial Technology Research Institute (ITRI) in Taiwan, developing cutting-edge security measures and techniques.</p>
    <p>Additionally, Sanoop served as an Assistant Professor in the Department of Information and Communication Technology at Manipal Institute of Technology, Manipal University in India, for 6.5 years. His teaching and mentorship have inspired numerous students in the field of computer science.</p>
    <p>His research interests lie in dependable systems security, automated vulnerability discovery through fuzzing systems, and data protection and privacy. Sanoop is dedicated to advancing the landscape of cybersecurity and fostering a deeper understanding of security challenges in today's digital environment.</p>
    <a id="toggleLinkEnd" href="#" onclick="toggleContent()" style="display: block; margin-top: 10px;">Read less</a>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/marked/4.0.12/marked.min.js"></script>

<div class="justified-text justified-text-color interests">
  <p style="font-size: 20px; color: #2a9d8f;"><em>Interests:</em></p>
  <ul>
    <li><a href="/my_reports/DSS.html" target="_blank"><em>Dependable Systems Security</em></a></li>
    <li><a href="/my_reports/AI_CYS.html" target="_blank"><em>AI-Driven Cyber Security</em></a></li>
    <li><a href="/my_reports/AML.html" target="_blank"><em>Adversarial ML</em></a></li>
    <li><a href="/my_reports/SSD.html" target="_blank"><em>Secure Software Development</em></a></li>
    <li><a href="/my_reports/XAI.html" target="_blank"><em>Trustworthy/Explainable AI</em></a></li>
    <li><a href="/my_reports/DPP.html" target="_blank"><em>Data Privacy Preservation</em></a></li>
    <li><a href="/my_reports/CPS.html" target="_blank"><em>Critical Infrastructure & CPS Security</em></a></li>
    <li><a href="/my_reports/BCA.html" target="_blank"><em>Blockchain Technology & Applications</em></a></li>
  </ul>
</div>

<script>
function toggleContent() {
    var content = document.getElementById("extraContent");
    var toggleLink = document.getElementById("toggleLink");
    var toggleLinkEnd = document.getElementById("toggleLinkEnd");

    if (content.style.display === "none") {
        content.style.display = "block";
        toggleLink.style.display = "none";
        toggleLinkEnd.style.display = "block";
    } else {
        content.style.display = "none";
        toggleLink.style.display = "block";
        toggleLinkEnd.style.display = "none";
    }
}
</script>


{{< icon name="download" pack="fas" >}} {{< staticref "uploads/resume.pdf" "newtab" >}}Resume{{< /staticref >}}
