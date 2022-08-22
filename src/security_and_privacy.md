# Security and privacy of user data

Personal details may be processed within Argu. When users register, they provide their e-mail address. In addition, administrators can set up certain fields that contain personal data.

Our [Privacy policy](https://argu.co/argu/privacy) describes how we deal with personal data.

## Does Argu comply with the AVG / GDPR?

Yes, we take privacy extremely seriously and adhere to the General Data Protection Regulation.

## Is Argu a data controller?

Usually yes, but as a customer you can choose to enter into your own privacy agreement with the users of your Argu website. In that case, we as Argu are _processor_ rather than _processing agent_. We will draw up a _processing agreement_ with you in that case.

## Security & privacy measures

- We always use [SSL encrypted](https://www.ssllabs.com/ssltest/analyze.html?d=argu.co&latest) HTTPS connections in external connections and we use DNSSEC to encrypt our DNS records. We score [100% on internet.nl](https://internet.nl/site/argu.co/803966/) because of such measures.
- Only specific employees have database access. Access is via an encrypted SSH connection, and is protected with a firewall from Cloud66 (the [CX tool](https://github.com/cloud66-oss/cx)).
- All accounts for critical infrastructure use two-factor authentication (2FA).
- We run automated dependency vulnerability checks and static code analysis (rubocop, brakeman) with every deploy.
- Where we collect [visitor statistics](https://argu.co/argu/t/10532), we do so with the self-hosted software Matomo, and there we always remove the last three or six numbers of IP addresses.
- We use strict CSP and CORS settings, so that cross-site scripting attacks are not possible.
- Employees may only have sensitive data (such as Argu production data) on their laptops in exceptional situations, and may only store it in encrypted form.
- We maintain a whitelist for attachment extensions, making it more difficult to spread malware.
