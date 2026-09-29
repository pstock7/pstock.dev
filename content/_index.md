+++
+++

{{ profile_header(
    name="Patrick Stock",
    subtitle="DSP Software Engineer",
    summary="DSP software engineer focused on radio signal processing, containerized services, and software-defined radio integration. Experienced developing and testing mission-critical applications and supporting on-site integration events to ensure systems are ready for deployment.",
    image="/profile-photo.avif",
    github="https://github.com/pstock7",
    email="pstockdev@gmail.com",
    linkedin="https://www.linkedin.com/in/patricktstock/",
    resume="/patrick-stock-resume.pdf"
) }}

## Skills

<div class="skills-card">
  <div class="skills-grid">
    <section class="skill-group">
      <h3>Languages</h3>
      <p>Python, C++, C, Rust, Lua, JavaScript, Java, Nix, Bash</p>
    </section>
    <section class="skill-group">
      <h3>Signal Processing</h3>
      <p>X-Midas, signal detection and validation, spectrum analysis, software-defined radio integration (Ettus, HTL)</p>
    </section>
    <section class="skill-group">
      <h3>Systems & Messaging</h3>
      <p>Linux, Docker, containerized distributed services, ActiveMQ</p>
    </section>
  </div>
</div>

## Experience

{% resume_card(title="DSP Software Engineer",
               organization="Parsons",
               location="Herndon, Virginia",
               date="June 2024 - Present") %}

- Serve as a software subject-matter expert at on-site integration events, resolving SDR configuration, signal detection, and distributed-service issues across containerized systems.
- Develop Python services for processing radio IQ data and coordinating Docker containers through an ActiveMQ message broker.
- Designed and implemented an end-to-end RF test service that transmits known signals between system instances and validates resulting detections through the message broker.
- Act as the primary software point of contact for a customer project, supporting integration questions and maintaining continuity for its software architecture.

{% end %}

{% resume_card(title="DSP Software Intern",
               organization="Parsons",
               location="Herndon, Virginia",
               date="Summer 2022 & Summer 2023") %}

- Developed a containerized Python application for real-time spectrum visualization, radio control, and signal recording and analysis, including waterfall displays, time-selective and frequency-selective recording, storage-capacity estimates, and tools for reviewing completed recordings.
- Operated SDR equipment and served as a hardware and software resource during a customer demonstration.
- Created a VPN service enabling radios to communicate across networks.
{% end %}

## Education

{% resume_card(title="Master of Science in Computer Engineering",
               organization="Virginia Tech",
               location="Online",
               date="August 2024 - Present") %}

- **Focus:** Networking & Cybersecurity
- **Courses Completed:** Information Theory, Network Architecture and Protocols, System and Software Security
{% end %}

{% resume_card(title="Bachelor of Science in Computer Engineering",
               organization="Virginia Tech",
               location="Blacksburg, Virginia",
               date="August 2020 - May 2024") %}

- **Focus:** Machine Learning
- **Minors:** Computer Science, Cybersecurity, Math
- **Courses Completed:** Network Application Design, Advanced Machine Learning, Computer Organization and Architecture, Computer and Network Security, Embedded Systems, Computer Vision, Cryptography, Artificial Intelligence and Engineering Applications

{% end %}
