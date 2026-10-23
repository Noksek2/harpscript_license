# FAQ - about `harpscript license 1.0`
# Is this repository legally binding?
Even as a custom source code license, as long as the copyright holder and repository administrator possess the copyright and distribution rights, this license is interpreted as fully legally binding.

# "Illegal use" can be ambiguous. What does it exactly mean?
Legal judgments and procedures vary by jurisdiction and involve complex matters, making it impossible for this repository to oversee everything directly. However, the following actions are considered blatant license violations and illegal acts:

Using the code from this repository for explicitly unlawful purposes, such as malware, virus distribution, or cracking.

Attempting to launder (dilute) the license: Using generative AI, LLM chatbots/agents, or other bypass tools to dilute or strip the Harpscript license.

These constitute fundamentally severe license violations. Any legal responsibilities and risks resulting from such actions must be borne entirely by the violator.

# What about commercial use?
Unless the administrator has specified separate restrictions at the top of the repository's NOTICE, LICENSE, or README files, commercial use is permitted by default.

However, in the event of detailed legal disputes arising when no specific conditions are stated in the repository, we cannot provide definitive legal interpretation or protection from our side.

# Is the code free to use?
As long as you comply with the README and the license obligations mentioned above (source crediting, keeping the repository private, etc.), internal use of the code itself is not restricted.

However, we emphasize again: Extreme caution is required when uploading publicly. Ignoring these conditions is immediately considered a license violation.

# One question: Why create such an inconvenient license?
We regret any inconvenience users may experience. However, convenience aside, this decision is strictly based on the "principle of code protection."

The modern open-source community severely lacks adequate code protection policies, sanctions, and license compliance enforcement against unauthorized learning by AI tools.

Even though not all open-source projects have permitted AI training, their code is indiscriminately collected for datasets, posing a serious ethical issue.

From a development ethics perspective, this is a minimal defense line built to prevent one's code from being consumed without permission as a tool for commercial AI.

We ask that you evaluate the intent of the Harpscript license with an understanding of these underlying issues.

# Are there conflicts with other licenses? (Currently under interpretation, subject to change)
As of October 23, 2026, the interpretation is as follows:

Permissive licenses (MIT, Apache License 2.0, BSD, etc.): Can be used together.

MPL 2.0: Interpreted as usable.

GPL / LGPL: Fundamentally incompatible due to the viral nature of GPL/LGPL.

The Harpscript license is built upon "code protection" as its utmost priority. Therefore, if code under this license is publicly uploaded to GitHub or other unprotected platforms outside of Codeberg, license violations and contractual conflicts will arise.

The Harpscript license's "viral nature (restrictive condition)" triggers only upon public upload. Therefore, even if you use this code internally within a project based on another license, you must exclude the repository containing Harpscript code from public uploads (keeping it strictly private) and explicitly credit the original source to remain free from legal issues.

## IMPORTANT: Compatibility with Copyleft licenses like GPL and LGPL
Regardless of whether the project is private or public, this license is fundamentally highly likely to be incompatible with licenses like GPL and LGPL that enforce mandatory source code disclosure for derived works. Combining them is NOT permitted.

The Core Conflict (Viral nature of GPL): GPL/LGPL mandates that any derived projects or sub-repositories connected to their code must be publicly disclosed (open-sourced). This directly clashes with the Harpscript license's core principle: "the obligation to keep original code private and isolated on unprotected platforms."

Application Principle: It is impossible to publicly distribute or release a GPL/LGPL-based project that includes Harpscript code.

Therefore, combining and distributing is only partially possible with permissive licenses (like MIT or Apache 2.0) that do not force the public disclosure of derived source code, provided that the condition to privately isolate the Harpscript code is strictly met.

Note: Any GPL violations are outside the jurisdiction of Harpscript. In the event of a GPL violation, the violator is subject to the penalty principles of the GPL itself.

## Compatibility with Permissive Licenses (MIT, Apache, MPL, etc.)
When used privately: Under current standards, it is interpreted as not conflicting with widely known standard open-source licenses (MIT, Apache, MPL, etc.).

When distributed publicly: It may conflict with the vast majority of current open-source projects. This is because the existing open-source ecosystem is left defenseless against unauthorized crawling and external scraping. Therefore, when publicly distributing other open-source projects, you are obligated to exclude (privately isolate) the Harpscript-related parts.

# Why limit exclusively to Codeberg?
By the standards of the license administrator (Noksek2), Codeberg adheres to the principle of explicitly blocking AI training and unauthorized crawling, making it uniquely independent and reliable among current open-source hosting platforms.

Simultaneously, given its clear stance on code protection amidst modern digital regulatory environments like the EU AI Act, we consider it the "only stronghold" where we can currently permit public uploads.

There is absolutely no intention to promote a specific platform. This decision is based entirely on the license administrator's code protection principles, and we hope there are no misunderstandings regarding this.

# Is execution on GPL-based OS environments like Linux an issue?
Simple execution and independent operation (Safe): Running or operating as an independent program using the Linux kernel's system calls is not subject to GPL's viral nature. You can freely use it while maintaining the conditions of the Harpscript license (keeping it private / source crediting).

Direct source code combination (Prohibited): Actions such as directly merging GPL code into the Harpscript project or strongly linking them into a single binary for public distribution are not permitted, as the obligations of the two licenses inherently contradict each other.
