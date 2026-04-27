## Hi there 👋

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Kenny's Resume</title>
        <link rel="stylesheet" href="../style/style.css">
    </head>
    <body style="font-family: Arial, Helvetica, sans-serif;">
        <header id="main-header">
            <h1>Kenny's Resume</h1>
            <div id="date-display"></div>
            <nav>
                <ul>
                    <li><a href="CoverSheet.html">CoverSheet</a></li>
                    <li><a href="CareerGoals.html">Career Goals</a></li>
                </ul>
            </nav>
                     
        </header>
        <main>
         <!-- OBJECTIVE STATEMENT - KL 040726 -->
          <section id="objective-statement">         
            <h3 class="sectionHeader">OBJECTIVE</h3>
            <p>Driven <strong>IT Support Specialist</strong> and current WGU student with over 30 years of technical maintenance and logistics experience. I am leveraging expertise in Windows Server 2025, Active Directory, and network simulation to transition into advanced infrastructure management roles. My goal is to apply my veteran-led leadership and comprehensive IT certifications to enhance technical operations within a public sector environment.</p>
         </section>
         <hr>
         <!-- EXPERIENCE -->
         <section id="experience">
            <h3 class="sectionHeader">WORK EXPERIENCE</h3>
            <article>
                <h4 class="positionTitle">Computer Technician | <span class="employeeName">BCPS, NJ</span></h4>
                <p>10/2024 - Present</p>
                <ul>
                        <li>Provide IT support for over 1000 faculty, staff and students.</li>
                        <li>Resolve over 20 support tickets per week using the ServiceDesk platform.</li>
                        
                </ul>

                <h4 class="positionTitle">Signal Support Systems Specialist | <span class="employeeName">NJ National Guard </span></h4>
                <p>2/1990 - 10/2013</p>
                <ul>
                        <li>Installed, configured, and maintained desktops, laptops, printers, and peripherals.</li>
                        <li>Configured and troubleshooted LAN/WAN devices, switches, routers, and encryption equipment.</li>
                        
                </ul>
                                        
            </article>
         </section>            
            
               
            
       <hr>
         <!-- EDUCATION -->
         <section id="education">
            <h3 class="sectionHeader">EDUCATION</h3>
                 <p><a href="https://www.wgu.edu" target="_blank">Western Governors University</a> &nbsp; | &nbsp; Salt Lake City, UT</p>
                 <p>Bachelor of Science, Information Technology (Expected 10/2026, 103/121 credits completed)</p>
                
         </section>
        <hr>
         
        <section>
            <h3 class="sectionHeader">TECHNICAL SKILLS TABLE</h3>

            <table>
                <caption>Technical Skills Overview</caption>
                <!-- Table Headers -->
                <thead>
                    <tr>
                            <th>Systems & Infrastructure</th>
                            <th>Certifications</th>
                            <th>Networking & Security</th>
                            <th>Administrative Tools</th>
                    </tr>
                </thead>
                <!-- first table row -->
                <tbody>
                    <tr>
                            <td>Wndows Server 2025</td>
                            <td>CompTIA A+ / Network+</td>
                            <td>Cisco Packet Tracer</td>
                            <td>Active Directory / GPO</td>
                    </tr>
                    <!-- second table row -->
                    <tr>
                            <td>Windows 11 Enterprise</td>
                            <td>CompTIA Security+</td>
                            <td>VLAN & DHCP Config</td>
                            <td>Microsoft Entra ID</td>
                    </tr>
                    <!-- third table row -->
                    <tr>
                            <td>Oracle VirtualBox</td>
                            <td>ITIL v4 Foundation</td>
                            <td>Identity Management</td>
                            <td>Microsoft Intune</td>
                    </tr>
                </tbody>
                
            </table>
        
         <hr>
         <section>
         <h3>PROJECTS</h3>
            <h4>Systems Administration Home Lab (<em>Active Directory & Virtualization</em>)</h4>
                <ul>
                        <li>Provide IT support for over 1000 faculty, staff and students.</li>
                        <li>Resolve over 20 support tickets per week using the ServiceDesk platform.</li>
                        <li>Support users with Microsoft 365, Google Workspace, and educational software platforms.</li>
                </ul>
            <h4>Network Configuration & Simulation (Cisco Packet Tracer)</h4>
                <ul>
                        <li>Installed, configured, and maintained desktops, laptops, printers, and peripherals.</li>
                        <li>Configured and troubleshooted LAN/WAN devices, switches, routers, and encryption equipment.</li>
                        <li>Trained and supervised soldiers on proper use of communications equipment and IT systems.</li>            
                </ul>
            </section>
         <hr>
        
         <!-- CONTACT INFORMATION -->
        <section id="contactInfo">
            <p>Kenny <br> Newark, NJ 08010 <br> kenny@wgu.edu</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 | IT Professional Portfolio </p>
                <p>Kenny | New Jersey</p>
            <div class="footer-section">
                <p><strong>Connect:</strong></p>
                <a href="mailto:yourname@email.com">Email Me</a>
            </div>
    </footer>

    <script>
        // Date into the div
        document.getElementById("date-display").innerHTML = "Date: " + new Date().toDateString();
        // Value to the console
      console.log("Site complete");         
    </script>
    </body>
</html>
