# rhel
A handy tool for checking vulnerability CVEs against Red Hat.

A bash script to output the first fixed software version from Red Hat
for the provided RHEL version (5, 6, 7) and CVE or CVE list separated by spaces.
Also attempts to grab CVSS and DoS info for PCI reasons.

Usage is ./rhel <red_hat_version> <cve/cvelist>
