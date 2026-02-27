# cncf-Gbg-march-2026-workshop braindump
Presentations and other useful stuff used during the workshop
## Part 1 Change from Go upstream image with jundreds of CVEs to a multi-stage build with zero CVEs
1. Clone https://github.com/chainguard-dev/learning-labs-static/
2. Read preso CNCF Gbg Feb 25 Build Secure and Minimal Images with Chainguard Static Images, part 1
3. Follow my notes of steps in steps.txt (yes, just notes, not 100% well documented)
4. If done correclty you should endup with a Dockerfile that looks like Dockerfile.multi-static
## Part 2 Sign an image using Cosign
Follow the guide at: https://edu.chainguard.dev/open-source/sigstore/cosign/how-to-sign-an-sbom-with-cosign/

Bonus: implement an admission controller to make sure that only signed images are used :-) https://edu.chainguard.dev/open-source/sigstore/policy-controller/how-to-install-policy-controller/
## Part 3 Dig into how scanners works, and howto trick them, and detect a tampered image using signautures
Read preso CNCF-Gbg Edgecases part 2

Clone https://github.com/maligin/edgecase-2025

Take a look at the scripts and understand what they do
