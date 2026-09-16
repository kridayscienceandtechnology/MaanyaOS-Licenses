MAANYAOS™ SECURITY, CRYPTOGRAPHY, DATA PROTECTION & SECURITY RESEARCH LICENSE

Version 1.0 — September 2026

Copyright © 2026 Kriday Ghosh. All Rights Reserved with respect to original proprietary MaanyaOS security technology.

---

1. PURPOSE

This License governs original MaanyaOS technology relating to:

- system security;
- cryptographic functionality;
- encryption;
- hashing;
- key management;
- authentication;
- authorization;
- secure boot;
- package verification;
- software integrity;
- security monitoring;
- privacy protections;
- security tooling;
- security research;
- vulnerability handling;
- security-sensitive configuration;
- recovery mechanisms;
- protected system resources; and
- related security infrastructure.

---

2. SECURITY PRINCIPLE

MaanyaOS may implement multiple security mechanisms designed to reduce the risk of unauthorized access, tampering, data disclosure, malicious software, and system compromise.

No security mechanism can guarantee absolute security.

---

3. SECURITY IS A SYSTEM PROPERTY

Security depends upon the interaction of:

- hardware;
- firmware;
- boot components;
- kernel;
- drivers;
- applications;
- package sources;
- cryptographic keys;
- configuration;
- user behavior;
- network infrastructure;
- physical access; and
- third-party software.

A security feature in one component cannot guarantee security of the entire system.

---

4. CRYPTOGRAPHIC TECHNOLOGY

MaanyaOS may use cryptographic technologies for:

- confidentiality;
- integrity;
- authentication;
- digital signatures;
- secure communication;
- credential protection;
- package verification;
- disk encryption; and
- other security purposes.

---

5. AES-256

MaanyaOS may implement or support AES-256 or compatible AES configurations where technically appropriate.

Use of AES-256 does not constitute a guarantee that data protected using the system can never be compromised.

---

6. AES IMPLEMENTATION

The security of AES-based protection depends upon the correctness of:

- implementation;
- mode of operation;
- key generation;
- key storage;
- key management;
- initialization vectors or nonces;
- authentication mechanisms;
- system configuration; and
- surrounding software.

---

7. ENCRYPTION MODE

MaanyaOS may use authenticated or non-authenticated encryption modes depending on the relevant subsystem.

Users should consult applicable technical documentation for the security properties of a particular implementation.

---

8. AUTHENTICATED ENCRYPTION

Where appropriate, MaanyaOS may use authenticated-encryption constructions to provide confidentiality and integrity.

---

9. HASHING

MaanyaOS may use cryptographic hash functions for:

- integrity verification;
- package verification;
- password-related operations;
- signatures;
- identifiers;
- content addressing; and
- security tooling.

---

10. SHA-256

MaanyaOS may use SHA-256 or compatible cryptographic hashing mechanisms.

---

11. SHA-512

MaanyaOS may use SHA-512 or compatible cryptographic hashing mechanisms.

---

12. HASHING IS NOT ENCRYPTION

Cryptographic hashing and encryption are different technologies.

A hash should not be treated as a reversible encryption mechanism.

---

13. PASSWORD STORAGE

Where MaanyaOS stores passwords or password-derived authentication data, appropriate password-protection mechanisms may be used.

Passwords should not ordinarily be stored as plaintext.

---

14. KEY GENERATION

Cryptographic keys should be generated using appropriately secure randomness where technically possible.

---

15. RANDOMNESS

Security-sensitive cryptographic operations may depend upon operating-system or hardware random-number sources.

Weak randomness may reduce cryptographic security.

---

16. KEY PROTECTION

Cryptographic keys may constitute highly sensitive security material.

Users are responsible for protecting keys under their control.

---

17. KEY LOSS

Loss of an encryption key may result in permanent loss of access to encrypted information.

MaanyaOS does not guarantee recovery of data for which the required cryptographic keys have been permanently lost.

---

18. KEY DISCLOSURE

Disclosure of a cryptographic key may compromise information protected by that key.

---

19. KEY ROTATION

MaanyaOS may provide mechanisms for cryptographic key rotation.

---

20. KEY REVOCATION

MaanyaOS may support key revocation or replacement where applicable.

---

21. COMPROMISED KEYS

Where a security key is believed to be compromised, users should replace or revoke it where technically possible.

---

22. BACKUP KEYS

Users may maintain secure backups of keys where appropriate.

Backups must themselves be protected from unauthorized access.

---

23. NO RECOVERY GUARANTEE

MaanyaOS does not guarantee recovery of encrypted information where required cryptographic credentials are unavailable.

---

24. FULL-DISK ENCRYPTION

MaanyaOS may support full-disk or block-device encryption.

---

25. FILE ENCRYPTION

MaanyaOS may provide file-level encryption mechanisms.

---

26. DIRECTORY ENCRYPTION

MaanyaOS may provide encrypted directories or equivalent protected storage.

---

27. DEVICE ENCRYPTION

MaanyaOS may support encryption of removable or secondary storage devices.

---

28. REMOVABLE MEDIA

Users remain responsible for protecting encrypted removable media and its associated credentials.

---

29. RECOVERY CREDENTIALS

Recovery keys or recovery credentials may provide access to protected data.

Users are responsible for protecting recovery credentials.

---

30. RECOVERY FAILURE

If required recovery information is unavailable, MaanyaOS may be unable to restore access to encrypted data.

---

31. SECURE BOOT

MaanyaOS may support or integrate secure-boot technologies.

---

32. BOOT INTEGRITY

Secure-boot mechanisms may verify the integrity or authenticity of boot components.

---

33. BOOT KEYS

Boot-signing keys may constitute security-sensitive credentials.

---

34. SIGNED KERNELS

MaanyaOS may support digitally signed kernels or kernel modules.

---

35. SIGNED PACKAGES

MaanyaOS may use cryptographic signatures to verify package authenticity.

---

36. SIGNED UPDATES

Official MaanyaOS updates may be digitally signed.

---

37. UPDATE INTEGRITY

MaanyaOS may verify updates before installation.

---

38. REPOSITORY SECURITY

MaanyaOS may verify repository metadata and package signatures where supported.

---

39. TRUSTED SOURCES

Users should obtain software from sources they reasonably trust.

---

40. THIRD-PARTY SOFTWARE

Third-party software may contain vulnerabilities independent of MaanyaOS.

---

41. THIRD-PARTY PACKAGES

Installation of third-party packages may introduce security risks.

---

42. THIRD-PARTY REPOSITORIES

Third-party repositories are not necessarily operated or controlled by MaanyaOS.

---

43. UNTRUSTED SOFTWARE

Users who knowingly install untrusted software may expose the system or data to security risks.

---

44. MALWARE

MaanyaOS may attempt to detect, prevent, isolate, or mitigate malware.

No security system guarantees detection of every malicious program.

---

45. RANSOMWARE

MaanyaOS may provide security mechanisms intended to reduce risks associated with ransomware and unauthorized file modification.

No such mechanism guarantees prevention of every ransomware incident.

---

46. ROOTKITS

MaanyaOS may provide mechanisms intended to detect or prevent certain rootkit behaviors.

Detection of every rootkit is not guaranteed.

---

47. SUPPLY-CHAIN SECURITY

MaanyaOS may implement supply-chain security controls including:

- signed packages;
- checksums;
- reproducible builds;
- provenance;
- trusted repositories;
- source verification; and
- build verification.

---

48. SOFTWARE SUPPLY CHAIN

Security of the software supply chain depends upon upstream projects, build infrastructure, repositories, signing infrastructure, and deployment systems.

---

49. BUILD INFRASTRUCTURE

Compromise of build infrastructure may affect the integrity of resulting software.

---

50. REPOSITORY COMPROMISE

A compromised repository may distribute malicious or modified software.

---

51. SIGNING KEY COMPROMISE

Compromise of a legitimate signing key may undermine signature-based trust.

---

52. KEY COMPROMISE RESPONSE

MaanyaOS may revoke, rotate, replace, or invalidate compromised signing credentials where technically possible.

---

53. SECURITY UPDATES

MaanyaOS may distribute security updates for supported components.

---

54. SECURITY ADVISORIES

MaanyaOS may publish security advisories describing identified vulnerabilities.

---

55. VULNERABILITY DISCLOSURE

Security researchers are encouraged to report vulnerabilities through appropriate MaanyaOS security channels where such channels are provided.

---

56. RESPONSIBLE DISCLOSURE

Researchers should, where reasonably possible, provide sufficient information to reproduce and understand a vulnerability without unnecessarily exposing users to additional risk.

---

57. SECURITY RESEARCH

Security research involving MaanyaOS should be conducted responsibly and in accordance with applicable law.

---

58. AUTHORIZED TESTING

Testing should be limited to systems and data for which the researcher has appropriate authorization.

---

59. UNAUTHORIZED ACCESS

Nothing in this License grants authorization to access systems, accounts, networks, repositories, or data belonging to another person.

---

60. NO SECURITY BYPASS AUTHORIZATION

Nothing in this License authorizes circumvention of authentication, authorization, access-control, licensing, or security mechanisms belonging to third parties.

---

61. VULNERABILITY TESTING

Security testing may include controlled testing of:

- authentication;
- authorization;
- package integrity;
- cryptographic implementations;
- system permissions;
- sandboxing;
- network interfaces;
- APIs; and
- other security mechanisms.

---

62. DATA PROTECTION

MaanyaOS may provide security mechanisms intended to protect user data.

---

63. USER DATA

User data remains under the control and responsibility of the user or applicable data controller.

---

64. DATA CONFIDENTIALITY

Encryption and access-control mechanisms may reduce unauthorized disclosure risk.

They do not guarantee absolute confidentiality.

---

65. DATA INTEGRITY

MaanyaOS may use hashes, signatures, authenticated encryption, filesystem integrity mechanisms, or other technologies to detect unauthorized modification.

---

66. DATA AVAILABILITY

Security mechanisms do not guarantee continuous availability of user data.

---

67. DATA LOSS

Data may be lost because of:

- hardware failure;
- software failure;
- user error;
- malware;
- accidental deletion;
- filesystem corruption;
- failed updates;
- power loss;
- cryptographic key loss;
- physical damage;
- unsupported configuration; or
- other circumstances.

---

68. USER-CAUSED DATA LOSS

To the extent permitted by applicable law, MaanyaOS and its rights holder are not responsible for data loss resulting from actions performed by the user or from configurations controlled by the user.

---

69. USER MISCONFIGURATION

Security protections may be weakened by incorrect configuration.

Examples may include:

- disabling encryption;
- disabling secure boot;
- disabling firewall controls;
- granting excessive permissions;
- exposing administrative interfaces;
- installing untrusted software; or
- disabling security updates.

---

70. ADMINISTRATIVE ACTIONS

Users with administrative privileges can make changes capable of affecting the security and integrity of the operating system.

---

71. ROOT ACCESS

Commands executed with root or equivalent privileges may modify critical system resources.

Users are responsible for commands they intentionally execute with such privileges, subject to applicable law.

---

72. SUDO

Where sudo is used, sudo remains independently licensed software.

MaanyaOS does not claim ownership of sudo.

---

73. PRIVILEGE ESCALATION

MaanyaOS may implement mechanisms intended to reduce unauthorized privilege escalation.

No mechanism guarantees prevention of every privilege-escalation vulnerability.

---

74. ACCESS CONTROL

MaanyaOS may implement access-control mechanisms governing files, processes, services, devices, and other resources.

---

75. FILE PERMISSIONS

Filesystem permissions may restrict access to protected resources.

---

76. SERVICE PERMISSIONS

System services may operate with elevated privileges.

Incorrect service configuration may introduce security risks.

---

77. SANDBOXING

MaanyaOS may provide sandboxing mechanisms for applications or services.

---

78. CONTAINMENT

Security isolation mechanisms may reduce the impact of compromised applications.

Isolation is not guaranteed to be perfect.

---

79. FIREWALL

MaanyaOS may provide firewall functionality.

Users remain responsible for appropriate firewall configuration.

---

80. NETWORK SECURITY

MaanyaOS may provide mechanisms including:

- firewalling;
- encrypted communications;
- certificate verification;
- network isolation;
- VPN integration; and
- network monitoring.

---

81. VPN

MaanyaOS may integrate VPN technologies.

VPN functionality does not guarantee anonymity, security, or privacy against every threat.

---

82. CERTIFICATE VALIDATION

MaanyaOS may validate TLS or other digital certificates where applicable.

---

83. CERTIFICATE TRUST

Certificate trust depends upon the configured trust store and validation mechanisms.

---

84. DNS SECURITY

MaanyaOS may support secure DNS technologies.

---

85. DNS DOES NOT GUARANTEE ANONYMITY

Secure DNS mechanisms do not guarantee complete anonymity or privacy.

---

86. HARDWARE SECURITY

MaanyaOS may use hardware security features where available.

Examples may include:

- TPM;
- secure elements;
- hardware-backed keys;
- CPU security features;
- secure boot;
- hardware random-number generators; and
- encrypted storage.

---

87. HARDWARE DEPENDENCY

Security functionality may depend upon hardware capabilities.

---

88. UNSUPPORTED HARDWARE

Security features may be unavailable or reduced on unsupported hardware.

---

89. FIRMWARE

Firmware may affect system security.

MaanyaOS does not claim ownership of third-party firmware.

---

90. BIOS AND UEFI

BIOS and UEFI implementations remain subject to their respective vendors' rights and licenses.

---

91. TPM

TPM functionality may depend upon hardware and firmware implementation.

---

92. HARDWARE COMPROMISE

A compromised hardware platform may undermine operating-system security.

---

93. PHYSICAL ACCESS

Physical access to a device may provide opportunities to bypass or weaken certain software security controls.

---

94. LOST DEVICES

Users should treat lost or stolen devices as potentially compromised.

---

95. CREDENTIALS

Users are responsible for protecting:

- passwords;
- recovery keys;
- private keys;
- authentication tokens;
- API credentials;
- SSH keys;
- certificates; and
- other security credentials.

---

96. CREDENTIAL DISCLOSURE

MaanyaOS is not responsible for unauthorized use resulting from credentials voluntarily disclosed or negligently protected by the user, to the extent permitted by applicable law.

---

97. SHARED ACCOUNTS

Shared accounts may reduce accountability and security.

---

98. ACCOUNT SECURITY

Users should use appropriate authentication protections for security-sensitive accounts.

---

99. MULTI-FACTOR AUTHENTICATION

MaanyaOS may support or integrate multi-factor authentication.

---

100. SECURITY LOGGING

MaanyaOS may provide security logs.

---

101. LOG INTEGRITY

Security logs may be modified or deleted by sufficiently privileged users or attackers who compromise the system.

---

102. LOG AVAILABILITY

MaanyaOS does not guarantee that every security event will be logged.

---

103. SECURITY MONITORING

MaanyaOS may provide monitoring or alerting functionality.

Monitoring does not guarantee detection of every security incident.

---

104. INCIDENT RESPONSE

MaanyaOS may provide mechanisms intended to assist with security incident response.

---

105. INCIDENT CONTAINMENT

MaanyaOS may isolate affected software, disable services, revoke credentials, or restrict package sources where technically appropriate.

---

106. SECURITY RECOVERY

MaanyaOS may provide recovery tools for compromised systems.

---

107. REINSTALLATION

A compromised system may require reinstallation or restoration from a trusted backup.

---

108. BACKUPS

Users should maintain appropriate backups of important data.

---

109. BACKUP SECURITY

Backups may contain sensitive information and should themselves be protected.

---

110. BACKUP VERIFICATION

Users should periodically verify that important backups can actually be restored.

---

111. BACKUP LIMITATION

The existence of a backup mechanism does not guarantee successful recovery from every failure.

---

112. ENCRYPTED BACKUPS

Encrypted backups may become inaccessible if required encryption credentials are lost.

---

113. CLOUD BACKUPS

Third-party cloud backup services remain subject to their own terms, security practices, and privacy policies.

---

114. THIRD-PARTY SECURITY SERVICES

Security services operated by third parties remain outside direct MaanyaOS control.

---

115. SECURITY DEPENDENCIES

MaanyaOS security may depend upon third-party libraries, kernels, firmware, cryptographic implementations, repositories, and hardware.

---

116. OPEN-SOURCE SECURITY

Open-Source components remain subject to their respective licenses and development processes.

---

117. LINUX SECURITY

Linux remains an independently developed Open-Source project.

MaanyaOS does not claim ownership of Linux.

---

118. CRYPTOGRAPHIC LIBRARIES

Cryptographic libraries integrated into MaanyaOS remain subject to their applicable licenses.

---

119. OPENSSL

Where OpenSSL is used, OpenSSL remains subject to its applicable licensing.

MaanyaOS does not claim ownership of OpenSSL.

---

120. LIBSODIUM

Where libsodium is used, libsodium remains subject to its applicable licensing.

MaanyaOS does not claim ownership of libsodium.

---

121. OTHER CRYPTOGRAPHIC COMPONENTS

Other cryptographic libraries and implementations remain subject to their respective licenses.

---

122. CRYPTOGRAPHIC IMPLEMENTATION RISK

Incorrect use or implementation of cryptographic primitives may introduce vulnerabilities even when the underlying algorithm is considered secure.

---

123. ALGORITHM SECURITY

No statement in this License guarantees that a particular cryptographic algorithm will remain secure indefinitely.

---

124. FUTURE CRYPTOGRAPHIC CHANGES

MaanyaOS may replace or update cryptographic algorithms where required for security or compatibility.

---

125. POST-QUANTUM SECURITY

MaanyaOS may investigate or implement post-quantum cryptographic technologies.

---

126. QUANTUM THREATS

Future advances in computing may affect the security assumptions of currently deployed cryptographic systems.

---

127. CRYPTOGRAPHIC AGILITY

MaanyaOS may design security infrastructure to permit replacement of cryptographic algorithms or parameters.

---

128. SECURITY CONFIGURATION

Security configuration may include:

- encryption settings;
- authentication policies;
- firewall rules;
- permissions;
- package sources;
- trust stores;
- signing keys;
- security policies; and
- system hardening settings.

---

129. HARDENING

MaanyaOS may provide hardened configurations.

Hardening does not guarantee immunity from compromise.

---

130. SECURITY PROFILES

MaanyaOS may provide different security profiles for desktop, server, enterprise, research, or other editions.

---

131. SERVER SECURITY

Server deployments may require additional security configuration appropriate to their environment.

---

132. DESKTOP SECURITY

Desktop users remain responsible for software installed and accounts configured on their systems.

---

133. ENTERPRISE SECURITY

Enterprise organizations remain responsible for implementing security controls appropriate to their infrastructure.

---

134. RESEARCH SECURITY

Research environments may intentionally enable experimental security functionality.

Experimental security features may be incomplete.

---

135. DEVELOPMENT SECURITY

Development builds may contain debugging functionality not appropriate for production systems.

---

136. DEBUGGING

Debug interfaces may expose information that would normally be protected.

---

137. TEST BUILDS

Development, nightly, beta, and experimental builds may have reduced security guarantees compared with supported stable releases.

---

138. RELEASE CLASSIFICATION

Security expectations may differ between:

- development;
- nightly;
- alpha;
- beta;
- release candidate;
- stable; and
- long-term-support releases.

---

139. PRE-RELEASE SECURITY

Pre-release software may contain undiscovered security vulnerabilities.

---

140. SECURITY RESEARCHER PROTECTION

Nothing in this License is intended to prohibit lawful security research conducted with appropriate authorization.

---

141. SECURITY RESEARCH BOUNDARY

Security research must not be interpreted as authorization to access systems or data without permission.

---

142. RESPONSIBLE DISCLOSURE CHANNEL

Where MaanyaOS publishes a security-reporting channel, researchers should use that channel for coordinated disclosure where practical.

---

143. EMBARGOES

MaanyaOS may coordinate disclosure timelines for vulnerabilities where doing so reduces risk to users.

---

144. CVE COORDINATION

Where appropriate, MaanyaOS may coordinate with recognized vulnerability-disclosure or CVE processes.

---

145. SECURITY ACKNOWLEDGEMENTS

MaanyaOS may acknowledge researchers who responsibly report vulnerabilities.

---

146. FALSE REPORTS

Security reports should be made in good faith and should contain accurate information to the best of the researcher's knowledge.

---

147. SECURITY TEST DATA

Researchers should avoid unnecessary collection or disclosure of personal, confidential, or sensitive data during testing.

---

148. PERSONAL DATA

Security testing should minimize exposure of personal information.

---

149. DATA MINIMIZATION

MaanyaOS security tooling may be designed to minimize unnecessary collection or retention of sensitive information.

---

150. TELEMETRY

Where telemetry exists, its behavior may be governed by separate MaanyaOS privacy documentation and applicable law.

---

151. NO ABSOLUTE SECURITY GUARANTEE

MaanyaOS does not represent that the system is completely immune to:

- malware;
- unauthorized access;
- data loss;
- cryptographic attacks;
- hardware compromise;
- software vulnerabilities;
- supply-chain attacks;
- credential theft;
- configuration errors; or
- other security incidents.

---

152. USER ERROR

To the extent permitted by applicable law, MaanyaOS and its rights holder are not responsible for security incidents caused by user-controlled configuration, intentional disabling of security controls, negligent credential handling, or unauthorized software installation.

---

153. USER MODIFICATIONS

Modifying MaanyaOS may change its security properties.

---

154. CUSTOM KERNELS

Custom kernels may introduce security risks not present in official builds.

---

155. CUSTOM MODULES

Third-party kernel modules may execute with highly privileged access.

---

156. CUSTOM DRIVERS

Third-party drivers may compromise system security or stability.

---

157. CUSTOM BOOTLOADERS

Modified bootloaders may affect boot integrity and secure-boot guarantees.

---

158. CUSTOM FIRMWARE

Modified or unofficial firmware may affect platform security.

---

159. UNOFFICIAL BUILDS

Unofficial MaanyaOS builds are not necessarily covered by the same security controls as official builds.

---

160. MODIFIED DISTRIBUTIONS

Third parties modifying MaanyaOS are responsible for the security properties of their modifications to the extent required by applicable law.

---

161. FORKS

A fork may diverge substantially from official MaanyaOS security infrastructure.

---

162. UNVERIFIED BINARIES

Users should exercise caution when executing binaries whose origin or integrity cannot be verified.

---

163. EXECUTION OF UNTRUSTED CODE

Users remain responsible for choosing whether to execute software obtained from sources they do not trust.

---

164. SECURITY DISCLAIMERS

Security features are provided on an as-available basis unless otherwise expressly stated in a separate written agreement.

---

165. NO GUARANTEE OF DATA RECOVERY

MaanyaOS does not guarantee recovery of data lost through encryption failure, deletion, corruption, hardware failure, malware, user error, or other causes.

---

166. NO GUARANTEE OF UNINTERRUPTED SECURITY

Security protection may be temporarily unavailable during:

- updates;
- maintenance;
- recovery;
- hardware failure;
- software failure; or
- other circumstances.

---

167. NO GUARANTEE AGAINST ATTACKS

No provision of this License constitutes a guarantee that MaanyaOS cannot be attacked or compromised.

---

168. LIMITATION OF LIABILITY

To the maximum extent permitted by applicable law, MaanyaOS and its rights holder shall not be liable for indirect, incidental, special, consequential, exemplary, or similar damages arising from use of or inability to use the security technology.

---

169. DATA LOSS LIMITATION

To the maximum extent permitted by applicable law, the rights holder shall not be liable for loss of data resulting from user-controlled actions, unsupported configurations, lost credentials, third-party software, hardware failure, or other circumstances outside reasonable control.

---

170. CRYPTOGRAPHIC RISK

Users acknowledge that cryptographic systems involve implementation, configuration, key-management, and operational risks.

---

171. NO PROFESSIONAL SECURITY GUARANTEE

Unless expressly agreed in writing, MaanyaOS does not constitute a guarantee that a deployment satisfies a particular security certification, regulatory standard, threat model, or compliance requirement.

---

172. SECURITY CERTIFICATIONS

Any future security certification shall apply only to the specific scope, version, configuration, and environment covered by that certification.

---

173. COMPLIANCE

Users remain responsible for determining whether their deployment complies with applicable laws, regulations, contractual requirements, and organizational security policies.

---

174. GOVERNMENT AND REGULATED SYSTEMS

Deployment in government, financial, medical, industrial, critical-infrastructure, or other regulated environments may require additional controls and agreements.

---

175. CRITICAL INFRASTRUCTURE

MaanyaOS does not guarantee suitability for critical infrastructure unless expressly evaluated and authorized for that purpose.

---

176. EXPORT AND CRYPTOGRAPHY LAWS

Users are responsible for complying with applicable laws governing cryptographic software, technology exports, imports, and use.

---

177. THIRD-PARTY RIGHTS

Nothing in this License grants rights to third-party cryptographic technology beyond rights already provided by its applicable license.

---

178. THIRD-PARTY LICENSE PRIORITY

Where a third-party license grants rights that cannot lawfully be restricted by this License, the applicable third-party license controls those rights.

---

179. OPEN-SOURCE PRIORITY

Open-Source components remain governed by their applicable Open-Source licenses.

---

180. PROPRIETARY SECURITY TECHNOLOGY

Original proprietary MaanyaOS security technology remains governed by applicable MaanyaOS licensing.

---

181. SECURITY DOCUMENTATION

Security documentation may describe configuration, architecture, threat models, cryptographic mechanisms, or operational procedures.

---

182. DOCUMENTATION ACCURACY

Security documentation is intended to describe the applicable implementation but may become outdated as software changes.

---

183. THREAT MODELS

MaanyaOS may publish threat models for specific components.

A threat model does not constitute a guarantee against threats outside its defined assumptions.

---

184. SECURITY ASSUMPTIONS

Security mechanisms may rely upon assumptions concerning:

- trusted hardware;
- trusted firmware;
- secure credentials;
- trustworthy package sources;
- correct configuration;
- protected physical access; and
- uncompromised dependencies.

---

185. BROKEN ASSUMPTIONS

If a security assumption fails, the corresponding security guarantees may no longer apply.

---

186. SECURITY BOUNDARIES

MaanyaOS may define security boundaries between:

- kernel and userspace;
- applications and system services;
- users and administrators;
- trusted and untrusted software;
- local and remote systems; and
- proprietary and third-party components.

---

187. PRIVILEGE BOUNDARIES

Crossing a security boundary may require explicit authorization.

---

188. SECURITY ARCHITECTURE

MaanyaOS may implement defense-in-depth using multiple independent security mechanisms.

---

189. DEFENSE IN DEPTH

Failure of one security mechanism does not necessarily imply failure of every other security mechanism.

---

190. SECURITY UPDATES FROM UPSTREAM

MaanyaOS may incorporate upstream security patches where applicable.

---

191. UPSTREAM VULNERABILITIES

Vulnerabilities in upstream components may affect MaanyaOS even when the original MaanyaOS code is not itself defective.

---

192. ZERO-DAY VULNERABILITIES

Previously unknown vulnerabilities may exist in MaanyaOS or its dependencies.

---

193. DISCLOSED VULNERABILITIES

Known vulnerabilities may remain exploitable until appropriate patches or mitigations are deployed.

---

194. PATCH AVAILABILITY

Security patches may depend upon upstream availability, engineering resources, hardware compatibility, or other factors.

---

195. SECURITY SUPPORT PERIOD

Security support may vary by MaanyaOS edition and release.

---

196. END OF SECURITY SUPPORT

Unsupported releases may no longer receive security updates.

---

197. MIGRATION

Users may be required to migrate to supported releases to receive future security fixes.

---

198. SECURITY CONFIGURATION CHANGES

Security updates may change default configuration or behavior where required to address vulnerabilities.

---

199. BREAKING SECURITY FIXES

Security fixes may occasionally introduce compatibility changes.

---

200. EMERGENCY SECURITY RESPONSE

MaanyaOS may issue emergency security releases where a serious vulnerability requires urgent mitigation.

---

201. SECURITY RELEASE AUTHENTICITY

Users should obtain security updates through official or otherwise trusted channels where possible.

---

202. SECURITY UPDATE VERIFICATION

Where signatures or hashes are provided, users should verify them where practical.

---

203. SECURITY REPOSITORIES

MaanyaOS may maintain dedicated security repositories or update channels.

---

204. SECURITY MIRRORS

Security repositories may be mirrored.

Mirrors must preserve applicable integrity and licensing requirements.

---

205. INCIDENT DISCLOSURE

MaanyaOS may disclose security incidents when appropriate and legally permissible.

---

206. PRIVACY INCIDENTS

Security incidents involving personal data may require additional handling under applicable law.

---

207. DATA BREACH RESPONSE

Organizations deploying MaanyaOS remain responsible for their own incident-response obligations.

---

208. USER NOTIFICATION

MaanyaOS may provide security notifications through available update or communication channels.

---

209. NO GUARANTEE OF NOTIFICATION

MaanyaOS cannot guarantee that every user will receive every security notification.

---

210. SECURITY RESEARCH LICENSE BOUNDARY

This License does not grant permission to attack third-party systems.

---

211. SAFE RESEARCH

Security research should use isolated, controlled, and authorized environments whenever practical.

---

212. RESPONSIBLE TOOLING

Security tools included with MaanyaOS may be intended for legitimate administration, auditing, research, and defense.

---

213. DUAL-USE SOFTWARE

Security tools may have legitimate defensive purposes while also being capable of misuse.

---

214. NO MALICIOUS AUTHORIZATION

Nothing in this License authorizes malicious deployment of security tooling.

---

215. NO UNAUTHORIZED SURVEILLANCE

Nothing in this License grants authorization to monitor or access another person's private systems or communications without appropriate authority.

---

216. NO UNAUTHORIZED DATA ACCESS

Nothing in this License grants permission to access, extract, modify, or disclose data belonging to another person without authorization.

---

217. SECURITY TOOL LICENSING

Third-party security tools remain governed by their respective licenses.

---

218. MAANYAOS SECURITY TOOLS

Original MaanyaOS security tools may be separately designated as proprietary.

---

219. SECURITY APIs

MaanyaOS may expose security APIs for applications or system components.

---

220. SECURITY API CHANGES

Security APIs may change between releases.

---

221. SECURITY PLUGINS

Security plugins may interact with privileged system resources.

Only trusted plugins should be installed in security-sensitive environments.

---

222. SECURITY EXTENSIONS

Third-party security extensions remain subject to their own licenses and security properties.

---

223. NO TRUST TRANSFER

Installing a security plugin does not automatically make it trustworthy or part of the MaanyaOS security boundary.

---

224. SECURITY CONFIGURATION BACKUPS

Backups of security configuration may contain sensitive information.

---

225. SECRET MANAGEMENT

MaanyaOS may provide mechanisms for storing or accessing secrets.

---

226. SECRET EXPOSURE

Users remain responsible for preventing unnecessary exposure of secrets.

---

227. ENVIRONMENT VARIABLES

Environment variables may contain sensitive credentials or configuration information.

---

228. LOGGED SECRETS

Applications should avoid writing sensitive credentials or secret material to logs.

---

229. DEBUG OUTPUT

Debugging tools may expose sensitive information.

---

230. SECURITY TEST ENVIRONMENTS

Security-sensitive experimentation should preferably use isolated environments and non-production data.

---

231. PRODUCTION SYSTEMS

Security testing against production systems should require appropriate authorization and safeguards.

---

232. SECURITY LIABILITY BOUNDARY

To the maximum extent permitted by applicable law, MaanyaOS does not assume responsibility for security consequences arising solely from user-controlled actions, unsupported modifications, third-party software, compromised credentials, or external infrastructure.

---

233. HARDWARE DAMAGE

Security-related software operations may interact with hardware, firmware, storage, or other system components.

To the maximum extent permitted by applicable law, MaanyaOS does not guarantee that every hardware configuration will remain unaffected by every software operation.

---

234. DATA CORRUPTION

Security operations, encryption operations, updates, recovery procedures, or user actions may result in data corruption in certain circumstances.

---

235. USER BACKUP RESPONSIBILITY

Users should maintain current backups before performing security-sensitive operations, encryption changes, system migrations, or major updates.

---

236. ENCRYPTION WARNING

Users should verify that they possess required recovery credentials before enabling encryption on important data.

---

237. DECRYPTION WARNING

Decryption may require credentials, keys, recovery information, or compatible software.

---

238. KEY DESTRUCTION

Intentional destruction or loss of encryption keys may make protected information permanently inaccessible.

---

239. SECURITY DEFAULTS

MaanyaOS may select security defaults intended to provide reasonable protection.

Defaults may not be appropriate for every threat model.

---

240. CUSTOM THREAT MODELS

Advanced users and organizations may configure MaanyaOS according to their own threat models.

---

241. NO THREAT MODEL GUARANTEE

No configuration can guarantee protection against every possible threat.

---

242. SECURITY PERFORMANCE

Security mechanisms may introduce computational, memory, storage, or network overhead.

---

243. HARDWARE ACCELERATION

MaanyaOS may use hardware acceleration for cryptographic operations where available.

---

244. CRYPTOGRAPHIC ACCELERATION

Hardware acceleration does not eliminate implementation or configuration risks.

---

245. SIDE-CHANNEL RISKS

Cryptographic implementations may be subject to side-channel or microarchitectural risks depending upon hardware and implementation.

---

246. TIMING ATTACKS

Security-sensitive implementations may attempt to reduce timing-related leakage where practical.

No guarantee against every side-channel attack is provided.

---

247. MEMORY SAFETY

Security may depend upon memory-safe or carefully reviewed implementations.

---

248. MEMORY DISCLOSURE

Memory corruption or information-disclosure vulnerabilities may compromise protected information.

---

249. SECURE MEMORY

MaanyaOS may implement mechanisms intended to reduce exposure of sensitive memory.

---

250. PROCESS ISOLATION

MaanyaOS may isolate processes using available operating-system security mechanisms.

---

251. KERNEL ISOLATION

Kernel-level compromise may undermine many userspace security mechanisms.

---

252. KERNEL SECURITY

Linux and other upstream kernel components remain subject to their own development and licensing processes.

---

253. MAANYAOS KERNEL MODIFICATIONS

Original MaanyaOS kernel modifications may be subject to applicable Open-Source or proprietary licensing depending upon the component.

---

254. SECURITY MODULES

Security modules may operate at privileged levels.

---

255. DRIVER SECURITY

Drivers may have highly privileged access to system resources.

---

256. FIRMWARE SECURITY

Firmware vulnerabilities may affect operating-system security.

---

257. MICROCODE

CPU microcode and related technologies remain subject to applicable vendor rights.

---

258. TRUSTED COMPUTING

Hardware-backed security mechanisms may improve resistance to certain attacks but do not guarantee complete protection.

---

259. SECURE STORAGE

MaanyaOS may use hardware-backed or software-based secure storage mechanisms.

---

260. SECURITY ARCHIVE

Historical security builds may no longer receive security updates.

---

261. LEGACY SYSTEMS

Older hardware may not support modern security mechanisms.

---

262. COMPATIBILITY VERSUS SECURITY

Maintaining compatibility with older hardware or software may require security trade-offs in certain circumstances.

---

263. SECURITY DEPRECATION

MaanyaOS may deprecate insecure algorithms, protocols, APIs, or configurations.

---

264. INSECURE LEGACY FEATURES

Legacy security features may be disabled or removed where continued support presents unacceptable security risks.

---

265. SECURITY POLICY

MaanyaOS may establish security policies governing supported configurations.

---

266. POLICY CHANGES

Security policy may change as threats, technologies, and supported environments evolve.

---

267. SECURITY GOVERNANCE

Original MaanyaOS security technology may be maintained according to project security policies.

---

268. SECURITY OWNERSHIP

Original proprietary MaanyaOS security technology is owned by Kriday Ghosh or the applicable rights holder, subject to third-party rights and Open-Source obligations.

---

269. THIRD-PARTY OWNERSHIP

Third-party security technologies remain owned by their respective rights holders.

---

270. NO OWNERSHIP CLAIM

Use or integration of a third-party cryptographic or security technology does not transfer ownership to MaanyaOS.

---

271. TRADE SECRETS

Unpublished MaanyaOS security architecture, keys, credentials, implementation details, and security research may constitute confidential information where expressly designated.

---

272. SECURITY CONFIDENTIALITY

Users receiving confidential security information should not disclose it where disclosure is prohibited by an applicable agreement.

---

273. RESPONSIBLE EMBARGO

Embargoed vulnerability information should not be publicly disclosed before the agreed disclosure date where legally enforceable.

---

274. SECURITY CREDENTIALS

MaanyaOS signing keys, private keys, infrastructure credentials, and authentication secrets may be confidential security assets.

---

275. NO CREDENTIAL LICENSE

Possession of MaanyaOS security documentation does not grant ownership or access to private cryptographic keys.

---

276. SECURITY INFRASTRUCTURE

MaanyaOS may operate security infrastructure including:

- signing systems;
- build servers;
- package repositories;
- vulnerability-reporting systems;
- update servers; and
- key-management infrastructure.

---

277. INFRASTRUCTURE SECURITY

Security of external infrastructure may depend upon providers outside MaanyaOS control.

---

278. SERVICE OUTAGES

Security infrastructure may become temporarily unavailable.

---

279. UPDATE OUTAGES

Temporary inability to obtain security updates does not itself constitute a guarantee that the system is secure.

---

280. SECURITY SUPPORT

Security support may be provided according to the applicable MaanyaOS edition or separate support agreement.

---

281. COMMERCIAL SECURITY SUPPORT

Commercial security support may be governed by separate written agreements.

---

282. ENTERPRISE SECURITY AGREEMENTS

Enterprise customers may receive additional security commitments only where expressly agreed in writing.

---

283. NO IMPLIED SLA

This License does not create a service-level agreement for security response times.

---

284. SECURITY RESPONSE PRIORITY

MaanyaOS may prioritize vulnerabilities according to severity, exploitability, affected users, available mitigations, and other technical factors.

---

285. SECURITY SEVERITY

Security severity classifications may change as additional information becomes available.

---

286. SECURITY FALSE POSITIVES

Security tooling may occasionally identify legitimate software or behavior as suspicious.

---

287. SECURITY FALSE NEGATIVES

Security tooling may fail to identify malicious software or behavior.

---

288. USER OVERRIDE

Where technically supported, users may override certain security warnings.

Users assume additional risk when disabling protective controls, subject to applicable law.

---

289. SECURITY LOCKOUT

Security controls may occasionally prevent legitimate access.

---

290. RECOVERY FROM LOCKOUT

Recovery may require administrative credentials or recovery procedures.

---

291. NO GUARANTEE OF ACCESS

MaanyaOS does not guarantee uninterrupted access to every protected resource.

---

292. SECURITY TESTING DISCLAIMER

Security testing may reveal vulnerabilities that were previously unknown.

Discovery of a vulnerability does not by itself establish negligence or liability.

---

293. SECURITY RESEARCH OUTPUT

Research results remain subject to applicable intellectual-property, confidentiality, privacy, and legal requirements.

---

294. PUBLICATION

Researchers may publish security findings subject to applicable law and any valid confidentiality obligations.

---

295. COORDINATED DISCLOSURE

Coordinated disclosure is encouraged where it reduces risk to affected users.

---

296. SECURITY CONTACT

MaanyaOS may publish an official security contact address or reporting mechanism.

---

297. SECURITY CONTACT CHANGES

Security reporting channels may change over time.

---

298. SECURITY ARCHITECTURE EVOLUTION

MaanyaOS security architecture may evolve between releases.

---

299. FINAL SECURITY PRINCIPLE

«Security technology reduces risk; it does not eliminate risk.»

---

300. FINAL CRYPTOGRAPHIC PRINCIPLE

«Strong cryptography cannot compensate for lost keys, compromised credentials, malicious software, insecure configuration, or compromised hardware.»

---

301. FINAL USER-RESPONSIBILITY PRINCIPLE

«Users remain responsible for the systems they configure, the software they install, the credentials they protect, and the data they choose to entrust to the system, subject to applicable law.»

---

302. FINAL DATA-LOSS PRINCIPLE

«MaanyaOS does not guarantee that user data can always be recovered after deletion, corruption, compromise, hardware failure, encryption failure, key loss, or other incidents.»

---

303. FINAL SECURITY BOUNDARY

Nothing in this License guarantees that MaanyaOS will prevent every:

- intrusion;
- malware infection;
- data breach;
- privilege escalation;
- cryptographic compromise;
- supply-chain compromise;
- hardware attack;
- firmware attack;
- credential theft; or
- other security incident.

---

304. GOVERNING LAW

This License shall be interpreted subject to applicable law.

To the extent legally permissible, disputes concerning original proprietary MaanyaOS security technology shall be subject to courts having competent jurisdiction in Delhi, India.

Nothing in this clause grants jurisdiction to a court that otherwise lacks lawful jurisdiction.

---

305. SEVERABILITY

If any provision is found unenforceable, the remaining provisions shall remain effective to the extent permitted by applicable law.

---

306. ENTIRE SECURITY LICENSE

This License governs the original proprietary MaanyaOS security, cryptography, and data-protection technology within its stated scope.

---

307. THIRD-PARTY LICENSE PRIORITY

Third-party software, cryptographic libraries, kernels, firmware, drivers, package managers, and other components remain governed by their respective licenses.

---

308. OPEN-SOURCE LICENSE PRIORITY

Nothing in this License overrides rights or obligations that cannot lawfully be restricted under an applicable Open-Source license.

---

309. PROPRIETARY COMPONENTS

Original proprietary MaanyaOS security components remain governed by applicable MaanyaOS proprietary licensing.

---

310. FINAL OWNERSHIP STATEMENT

Copyright © 2026 Kriday Ghosh.

All Rights Reserved with respect to original proprietary MaanyaOS security technology, subject to applicable third-party rights and Open-Source licensing obligations.

END OF LICENSE