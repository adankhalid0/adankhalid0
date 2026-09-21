Hei, jeg heter Khalid 👋

Cybersecuritystudent med bred interesse for faget med mest fokus på cloud security og offensiv sikkerhet i backend.

Jeg liker å forstå hvordan ting faktisk kan gå galt, og enda mer å finne ut hvordan man bygger og verifiserer at det ikke gjør det. Derfor bruker jeg fritiden på egne prosjekter ved siden av studiene — ikke for karakteren, men fordi jeg vil vise faktisk kompetanse fremfor bare teori. Dette repoet samler prosjektene der jeg bygger, angriper og forsvarer noe selv, dokumenterer det jeg finner, og tester at tiltakene faktisk virker.

Utvalgte prosjekter

headless-cms-pentest-case-study:
Anonymisert grey-box penetrasjonstest og full defensiv herding av en headless CMS-webapplikasjon (bacheloroppgave, karakter B). Inkluderer sladdet PoC-bevis for hvert funn og en uavhengig brukertest som bekrefter at sikkerhetsherdingen ikke gikk på bekostning av brukervennligheten.

Aws-cloud-security-baseline:
Sikker AWS-grunnmur bygget med Terraform, skannet med Checkov før utrulling og revidert med Prowler etterpå — 92 % CIS-compliance oppnådd, kritiske funn redusert fra flere til nesten null.

Aws-threat-detection-baseline:
Administrert trusseldeteksjon for AWS — GuardDuty og Security Hub koblet til en reell varslingspipeline med EventBridge og SNS, deployet med Terraform og skannet i CI. Følger opp aws-cloud-security-baseline: der revideres sikker konfigurasjon, her verifiseres det om noen faktisk oppdager det når noe går galt — testet end-to-end med GuardDutys egne test-funn, ikke bare i teorien.

Verktøy og teknologi

Terraform · Checkov · Prowler · GuardDuty · Security Hub · EventBridge · SNS · Burp Suite · OWASP ZAP · Nmap · Nikto · AWS · GitHub Actions
