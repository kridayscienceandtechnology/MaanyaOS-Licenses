MAANYAOS™ CRYPTOGRAPHIC STORAGE, TPM & PRIVACY ARCHITECTURE LICENSE

Version 1.0 — September 2026

Copyright © 2026 Kriday Ghosh. All Rights Reserved with respect to original proprietary MaanyaOS technology.

---

1. PURPOSE

This License governs original MaanyaOS technology relating to:

- cryptographic storage;
- disk encryption;
- filesystem encryption;
- AES-based encryption;
- cryptographic hashing;
- key generation;
- key storage;
- key derivation;
- TPM 2.0 integration;
- hardware-backed security;
- VeraCrypt integration;
- encrypted volumes;
- encrypted backups;
- recovery mechanisms;
- privacy-preserving architecture;
- local credential management;
- cryptographic metadata; and
- related security infrastructure.

---

2. PRIVACY PRINCIPLE

MaanyaOS is designed around the principle that private user data should remain under the user's control whenever technically and legally possible.

---

3. DATA OWNERSHIP

User-created data remains the property of the user or applicable rights holder.

MaanyaOS does not claim ownership of user files merely because those files are stored on or encrypted by a MaanyaOS system.

---

4. LOCAL-FIRST SECURITY

Where technically feasible, MaanyaOS may perform cryptographic operations locally on the user's device.

---

5. NO AUTOMATIC KEY ESCROW

Unless explicitly implemented and disclosed for a particular product or service, MaanyaOS does not intend to maintain a server-side copy of a user's private encryption keys.

---

6. NO IMPLICIT KEY ACCESS

The existence of MaanyaOS encryption functionality does not inherently provide MaanyaOS or its developer with access to a user's encryption keys.

---

7. ARCHITECTURAL PRIVACY

Where the implementation is designed without key escrow, the system operator may be unable to decrypt user data without the required user-controlled credentials or recovery material.

---

8. NO CLAIM BEYOND IMPLEMENTATION

Privacy claims apply only to the actual implementation and configuration deployed by the user.

---

9. AES

MaanyaOS may use the Advanced Encryption Standard (AES) for cryptographic protection.

---

10. AES-256

MaanyaOS may support AES-256 for appropriate encryption workloads.

AES-256 provides a cryptographic primitive; overall security additionally depends upon implementation, mode, key management, authentication, and system configuration.

---

11. AES-128

Where legacy or compatibility requirements exist, AES-128 may be supported.

---

12. AES-192

Where technically appropriate, AES-192 may be supported.

---

13. AES-256 DEFAULTS

Where MaanyaOS selects an AES configuration for high-security storage, AES-256 may be selected as an appropriate configuration.

---

14. AES-512 CLARIFICATION

AES itself is standardized with 128-bit block size and 128-, 192-, or 256-bit keys.

There is no standardized AES-512 variant in the AES standard.

MaanyaOS shall not describe a non-standard construction as "AES-512" merely to imply stronger security.

---

15. CUSTOM 512-BIT CONSTRUCTIONS

If MaanyaOS ever implements a proprietary 512-bit cryptographic construction, it must be separately documented and must not be represented as the AES standard.

---

16. CRYPTOGRAPHIC HONESTY

MaanyaOS shall distinguish between:

- standardized cryptographic algorithms;
- cryptographic constructions;
- proprietary cryptographic wrappers;
- key-derivation functions;
- hashing algorithms;
- encryption modes; and
- security protocols.

---

17. ENCRYPTION IS NOT A SINGLE FEATURE

The security of encrypted storage depends upon multiple layers including:

- algorithm;
- mode;
- key;
- key derivation;
- authentication;
- implementation;
- hardware;
- operating system;
- physical security; and
- user behavior.

---

18. AUTHENTICATED ENCRYPTION

Where appropriate, MaanyaOS may use authenticated encryption to provide both confidentiality and integrity.

---

19. NONCE MANAGEMENT

Cryptographic implementations requiring nonces must manage them according to the requirements of the relevant algorithm.

---

20. INITIALIZATION VECTORS

Where an encryption mode uses initialization vectors, MaanyaOS may generate and manage them according to the applicable cryptographic design.

---

21. KEY GENERATION

Encryption keys may be generated locally using cryptographically appropriate randomness.

---

22. RANDOMNESS

Security-sensitive operations may depend upon operating-system or hardware random-number generators.

---

23. KEY DERIVATION

User passwords may be transformed into encryption keys through an appropriate key-derivation mechanism.

---

24. PASSWORDS ARE NOT KEYS

A user-entered password should not ordinarily be treated as a raw cryptographic key.

---

25. SALTING

Password-derived cryptographic material may use salts where appropriate.

---

26. WORK FACTORS

Key-derivation mechanisms may use computational or memory costs designed to increase resistance against password-guessing attacks.

---

27. KEY STORAGE

Cryptographic keys may be stored using:

- encrypted key stores;
- TPM-backed protection;
- secure operating-system facilities;
- hardware-backed mechanisms; or
- user-controlled recovery material.

---

28. TPM 2.0

MaanyaOS may support Trusted Platform Module 2.0 (TPM 2.0) functionality where compatible hardware is available.

---

29. TPM OWNERSHIP

TPM technology remains subject to the applicable hardware, firmware, and specification rights.

MaanyaOS does not claim ownership of TPM technology merely because it integrates with TPM functionality.

---

30. TPM-BACKED KEYS

MaanyaOS may use TPM-backed keys or sealed secrets where technically supported.

---

31. TPM SEALING

Sensitive material may be sealed to selected platform state measurements or policies where supported.

---

32. TPM UNSEALING

A TPM may release protected material only when applicable authorization and platform conditions are satisfied.

---

33. TPM IS NOT A MAGIC SECURITY BOUNDARY

A TPM does not guarantee that every attack against a computer can be prevented.

---

34. TPM COMPROMISE

Security guarantees may be affected by vulnerabilities in TPM hardware, firmware, drivers, firmware configuration, or surrounding system software.

---

35. TPM AVAILABILITY

TPM-based functionality may be unavailable on systems without compatible TPM hardware or firmware.

---

36. SECURE BOOT

MaanyaOS may integrate TPM functionality with secure-boot or measured-boot mechanisms.

---

37. MEASURED BOOT

Where supported, platform measurements may be recorded for security verification or key-release policies.

---

38. BOOT STATE

Cryptographic access policies may depend upon the boot state of the device.

---

39. MODIFIED BOOT ENVIRONMENTS

Changing bootloaders, kernels, firmware, or security configuration may prevent TPM-protected secrets from being released.

---

40. RECOVERY

Users should maintain appropriate recovery mechanisms before enabling hardware-bound encryption.

---

41. TPM RESET

Resetting or clearing a TPM may affect TPM-protected keys or secrets.

---

42. KEY LOSS

Loss of required encryption keys, TPM state, recovery credentials, or passwords may result in permanent loss of access to encrypted information.

---

43. RECOVERY KEYS

MaanyaOS may provide or support recovery keys for encrypted storage.

---

44. RECOVERY KEY SECURITY

Recovery keys may provide substantial access to protected information and must therefore be protected accordingly.

---

45. NO RECOVERY GUARANTEE

MaanyaOS does not guarantee recovery of encrypted data when the required credentials or recovery mechanisms are unavailable.

---

46. VERACRYPT

MaanyaOS may integrate with or provide compatibility with VeraCrypt where technically and legally appropriate.

---

47. VERACRYPT OWNERSHIP

VeraCrypt remains an independent project subject to its applicable licensing and intellectual-property rights.

MaanyaOS does not claim ownership of VeraCrypt.

---

48. VERACRYPT COMPATIBILITY

Compatibility with VeraCrypt volumes does not imply ownership of VeraCrypt or its underlying cryptographic implementation.

---

49. THIRD-PARTY ENCRYPTED VOLUMES

MaanyaOS may provide tools for accessing encrypted volumes created by compatible third-party software.

---

50. VOLUME FORMAT

Encrypted volume formats may contain structures defined by third-party software.

MaanyaOS does not claim ownership of such third-party formats merely because it supports them.

---

51. ENCRYPTED VOLUMES

MaanyaOS may support encrypted:

- disks;
- partitions;
- filesystems;
- directories;
- removable media;
- backup containers; and
- virtual volumes.

---

52. FULL-DISK ENCRYPTION

Full-disk encryption may protect stored information when the device is powered off or otherwise inaccessible.

---

53. DATA AT REST

Encryption primarily protects data at rest according to the implemented threat model.

---

54. DATA IN USE

Encryption does not automatically protect information after it has been decrypted and is actively being used by applications.

---

55. DATA IN MEMORY

Once decrypted, sensitive information may exist in system memory.

---

56. MEMORY COMPROMISE

An attacker capable of sufficiently privileged memory access may potentially obtain sensitive information.

---

57. DATA IN TRANSIT

Network communications require separate transport-security mechanisms.

Disk encryption does not automatically encrypt network traffic.

---

58. ENCRYPTION BOUNDARIES

MaanyaOS may clearly distinguish between:

- data at rest;
- data in use; and
- data in transit.

---

59. ENCRYPTION METADATA

Certain metadata may remain visible even when file contents are encrypted.

---

60. FILE NAMES

Depending upon the encryption technology used, filenames may or may not be encrypted.

---

61. FILE SIZE

Depending upon the encryption technology used, file size or storage-allocation information may remain observable.

---

62. TIMESTAMPS

Filesystem timestamps or other metadata may remain observable depending upon the storage architecture.

---

63. TRAFFIC METADATA

Network traffic may expose metadata even when payload contents are encrypted.

---

64. PRIVACY LIMITATION

Encryption should not be represented as guaranteeing complete anonymity.

---

65. LOCAL KEY PROCESSING

Where designed accordingly, cryptographic keys may be processed locally on the user's device.

---

66. NO ROUTINE KEY TRANSMISSION

Where the architecture does not require remote key management, MaanyaOS does not intend to transmit private encryption keys to MaanyaOS infrastructure.

---

67. NO SECRET BACKDOOR

MaanyaOS does not intend to implement a hidden mechanism allowing the developer to bypass properly implemented user-controlled encryption.

---

68. NO MASTER PASSWORD

Unless explicitly documented for a particular enterprise or recovery product, MaanyaOS does not rely upon a universal developer-controlled master password for user encryption.

---

69. NO UNIVERSAL DECRYPTION KEY

MaanyaOS does not claim to maintain a universal decryption key for user-controlled encrypted storage.

---

70. NO DEVELOPER KEY ESCROW

Unless explicitly disclosed in a separate product or agreement, MaanyaOS does not maintain developer-controlled escrow of user encryption keys.

---

71. PRIVACY BY ARCHITECTURE

Where technically implemented, privacy protections may arise from architectural separation rather than promises made after the fact.

---

72. MINIMAL DATA COLLECTION

MaanyaOS may be designed to minimize unnecessary collection of user information.

---

73. SECURITY TELEMETRY

Security telemetry, if implemented, should be documented according to applicable MaanyaOS privacy documentation.

---

74. NO HIDDEN SECURITY TELEMETRY

MaanyaOS should not intentionally represent security telemetry as absent when the applicable build actually collects it.

---

75. TRANSPARENCY

Privacy and security claims should correspond to the actual released implementation.

---

76. OFFLINE CRYPTOGRAPHY

MaanyaOS may perform supported cryptographic operations entirely offline.

---

77. ONLINE SERVICES

Some optional services may require network connectivity.

Such services may have separate privacy and security terms.

---

78. SERVER-SIDE PROCESSING

Where cryptographic operations are performed server-side, applicable service documentation should identify that architecture.

---

79. LOCAL-FIRST DEFAULT

Where technically feasible, MaanyaOS may prefer local cryptographic processing over unnecessary remote processing.

---

80. ZERO-KNOWLEDGE TERMINOLOGY

The term "zero-knowledge" shall only be used for a specific architecture where the technical design actually satisfies the relevant zero-knowledge property.

---

81. NO MARKETING OVERCLAIM

MaanyaOS shall not describe ordinary encryption as "zero knowledge" merely because the developer does not ordinarily possess the user's password.

---

82. USER-CONTROLLED KEYS

Where supported, users may control the keys or credentials required to access protected data.

---

83. PASSWORD LOSS

If encryption depends upon a password and the password is permanently lost, MaanyaOS may be unable to recover the protected information.

---

84. RECOVERY MATERIAL

Recovery material should be stored separately from the primary device where practical.

---

85. RECOVERY STORAGE

Users may store recovery material using:

- offline storage;
- secure physical storage;
- encrypted backups; or
- other appropriately protected mechanisms.

---

86. RECOVERY MATERIAL DISCLOSURE

Disclosure of recovery material may compromise the confidentiality of protected data.

---

87. NO RECOVERY BACKDOOR

The absence of a developer-controlled recovery backdoor may be an intentional privacy and security characteristic.

---

88. FORGOTTEN CREDENTIALS

A forgotten password or lost recovery credential may result in irreversible loss of access.

---

89. ENCRYPTION ENABLEMENT

Users should understand the recovery consequences before enabling encryption.

---

90. ENCRYPTION DISABLEMENT

Disabling encryption may expose previously protected information.

---

91. KEY ROTATION

MaanyaOS may provide mechanisms for rotating or replacing cryptographic keys.

---

92. RE-ENCRYPTION

MaanyaOS may support re-encryption of data under a new key.

---

93. KEY DESTRUCTION

Secure destruction of encryption keys may make associated encrypted information permanently inaccessible.

---

94. DEVICE TRANSFER

Encrypted storage transferred to another device may require appropriate credentials, TPM state, or recovery material.

---

95. TPM-BOUND TRANSFER

Keys bound to a specific TPM or platform state may not automatically function on another device.

---

96. DEVICE REPLACEMENT

Users should prepare appropriate recovery mechanisms before replacing hardware.

---

97. HARDWARE FAILURE

Hardware failure may prevent access to TPM-protected or locally stored encryption keys.

---

98. SSD AND STORAGE FAILURE

Storage failure may result in loss of encrypted information.

Encryption does not substitute for backups.

---

99. BACKUP REQUIREMENT

Users should maintain backups of important data regardless of whether encryption is enabled.

---

100. ENCRYPTED BACKUPS

Backups may themselves be encrypted.

---

101. BACKUP KEY SEPARATION

Backup encryption keys should be protected separately from the primary device where appropriate.

---

102. BACKUP RECOVERY

A backup is useful only to the extent that it can actually be restored.

---

103. BACKUP TESTING

Users should periodically test important backup restoration procedures.

---

104. NO DATA-LOSS GUARANTEE

MaanyaOS does not guarantee against:

- accidental deletion;
- filesystem corruption;
- hardware failure;
- malware;
- ransomware;
- lost keys;
- lost passwords;
- failed updates;
- failed migrations;
- user error; or
- other causes of data loss.

---

105. USER RESPONSIBILITY

Users remain responsible for maintaining appropriate backups and recovery credentials.

---

106. PRIVACY RESPONSIBILITY

Users remain responsible for determining what information they store and where they store it.

---

107. THIRD-PARTY SERVICES

Cloud storage, synchronization, backup, email, analytics, and other third-party services may process information outside the MaanyaOS local security boundary.

---

108. CLOUD ENCRYPTION

Third-party cloud providers may use their own encryption architectures.

MaanyaOS does not automatically control those architectures.

---

109. SYNCHRONIZATION

Synchronizing encrypted or decrypted files may expose information depending upon the synchronization architecture.

---

110. APPLICATION ACCESS

Applications operating with appropriate permissions may access decrypted data.

---

111. MALWARE LIMITATION

Encryption cannot prevent an authorized application or malware operating with sufficient privileges from accessing data after it has been decrypted.

---

112. SCREEN AND DISPLAY PRIVACY

Encryption does not prevent information from being observed after it is displayed.

---

113. PHYSICAL OBSERVATION

Encryption does not prevent observation through cameras, screens, keyboards, or other physical means.

---

114. SIDE-CHANNELS

Cryptographic and hardware implementations may be subject to side-channel attacks.

---

115. TIMING INFORMATION

Certain implementations may expose timing-related information.

---

116. POWER ANALYSIS

Hardware-based attacks may potentially analyze power consumption or other physical signals.

---

117. ELECTROMAGNETIC ATTACKS

Specialized physical attacks may potentially exploit electromagnetic emissions.

---

118. HARDWARE SECURITY LIMITATION

Software encryption cannot guarantee protection against every physical attack.

---

119. TPM SECURITY LIMITATION

TPM-backed security does not guarantee protection against every hardware or firmware attack.

---

120. SECURE BOOT LIMITATION

Secure boot does not guarantee that every component executed after boot is trustworthy.

---

121. SUPPLY CHAIN

Cryptographic security depends upon the integrity of hardware, firmware, operating-system components, cryptographic libraries, and build infrastructure.

---

122. OPEN-SOURCE COMPONENTS

Third-party cryptographic and security components remain governed by their respective licenses.

---

123. OPENSSL

Where OpenSSL is used, OpenSSL remains subject to its applicable license.

---

124. LIBSODIUM

Where libsodium is used, libsodium remains subject to its applicable license.

---

125. VERACRYPT

VeraCrypt remains subject to its applicable project license and intellectual-property rights.

---

126. LUKS

Where Linux Unified Key Setup (LUKS) is used, its underlying implementation and associated components remain subject to their applicable licenses.

---

127. DM-CRYPT

Where dm-crypt is used, it remains part of the applicable Linux storage and cryptographic infrastructure and is not claimed as proprietary MaanyaOS technology merely because MaanyaOS integrates it.

---

128. TPM SOFTWARE STACK

TPM software stacks and utilities remain subject to their applicable upstream licenses.

---

129. TSS COMPONENTS

Trusted Computing Group-compatible software components and TSS implementations remain subject to their applicable licensing.

---

130. THIRD-PARTY CRYPTOGRAPHIC LIBRARIES

Third-party cryptographic libraries retain their independent licensing and copyright.

---

131. PROPRIETARY MAANYAOS CRYPTOGRAPHY

Original MaanyaOS cryptographic orchestration, configuration, interfaces, tooling, integration, and privacy architecture may constitute proprietary MaanyaOS technology where independently developed.

---

132. NO CLAIM OVER ALGORITHMS

MaanyaOS does not claim ownership over standardized cryptographic algorithms such as AES, SHA-2, or other publicly standardized primitives.

---

133. NO CLAIM OVER STANDARDS

Standards and specifications remain subject to their respective rights and licensing frameworks.

---

134. CRYPTOGRAPHIC IMPLEMENTATION RIGHTS

Any proprietary rights claimed by MaanyaOS apply only to original implementation or integration technology and not to third-party algorithms themselves.

---

135. SECURITY RESEARCH

Security researchers may analyze MaanyaOS cryptographic architecture subject to applicable law and authorization requirements.

---

136. VULNERABILITY DISCLOSURE

Security vulnerabilities should be responsibly reported through applicable MaanyaOS security channels where available.

---

137. CRYPTOGRAPHIC VULNERABILITIES

A vulnerability in an encryption implementation may undermine the security of data protected by that implementation.

---

138. EMERGENCY RESPONSE

MaanyaOS may issue emergency security updates affecting cryptographic functionality.

---

139. ALGORITHM DEPRECATION

MaanyaOS may deprecate cryptographic algorithms or configurations that become unsuitable for supported security requirements.

---

140. CRYPTOGRAPHIC AGILITY

MaanyaOS may support replacing cryptographic algorithms without requiring complete redesign of the storage architecture.

---

141. FUTURE ALGORITHMS

Future MaanyaOS releases may support additional cryptographic algorithms or post-quantum mechanisms.

---

142. POST-QUANTUM TRANSITION

MaanyaOS may evaluate post-quantum cryptography for future security requirements.

---

143. NO QUANTUM GUARANTEE

No current cryptographic configuration is represented as providing guaranteed protection against every future cryptanalytic development.

---

144. SECURITY UPDATES

Cryptographic components may receive security updates independently of other system components.

---

145. VERSION COMPATIBILITY

Changes to cryptographic libraries or storage formats may affect compatibility.

---

146. FORMAT MIGRATION

MaanyaOS may provide migration mechanisms when encrypted storage formats change.

---

147. LEGACY VOLUMES

Legacy encrypted volumes may remain accessible only while compatible cryptographic and filesystem components are available.

---

148. NO PERMANENT COMPATIBILITY

MaanyaOS does not guarantee permanent compatibility with every historical encryption format.

---

149. USER MODIFICATIONS

Modified encryption configurations may provide security properties different from official MaanyaOS configurations.

---

150. UNOFFICIAL BUILDS

Unofficial builds may change cryptographic behavior and should not automatically be considered equivalent to official releases.

---

151. CUSTOM KERNELS

Custom kernels may alter cryptographic or storage behavior.

---

152. CUSTOM CRYPTOGRAPHIC LIBRARIES

Replacing cryptographic libraries may change security properties and compatibility.

---

153. CUSTOM TPM CONFIGURATION

Changing TPM configuration may affect key availability and platform security.

---

154. SECURE ERASE

MaanyaOS may provide mechanisms intended to securely remove sensitive information.

---

155. STORAGE ERASE LIMITATIONS

Secure deletion behavior may depend upon storage technology, filesystem behavior, controller firmware, and hardware.

---

156. SSD LIMITATIONS

Traditional overwrite assumptions may not apply identically to modern solid-state storage.

---

157. ENCRYPTION AS DATA-DISPOSAL CONTROL

Where encryption is properly implemented and keys are securely destroyed, cryptographic erasure may provide a mechanism for making protected information inaccessible.

---

158. CRYPTOGRAPHIC ERASURE LIMITATION

Cryptographic erasure does not guarantee that every copy, backup, cache, or derivative of information has been destroyed.

---

159. CACHES

Applications or operating systems may temporarily cache information outside the primary encrypted storage boundary.

---

160. SWAP

Swap or hibernation storage may contain sensitive information depending upon system configuration.

---

161. HIBERNATION

MaanyaOS may encrypt or protect hibernation data where supported.

---

162. SLEEP STATES

Certain hardware sleep states may preserve sensitive information in memory.

---

163. MEMORY PROTECTION

MaanyaOS may implement available memory-protection mechanisms.

---

164. CREDENTIAL CACHING

Applications may cache credentials or decrypted information.

---

165. APPLICATION RESPONSIBILITY

Applications are responsible for appropriately protecting sensitive data they process.

---

166. PRIVILEGE BOUNDARIES

MaanyaOS security architecture may separate ordinary user privileges from administrative privileges.

---

167. ADMINISTRATOR TRUST

An administrator with sufficient privileges may be capable of accessing or modifying substantial portions of the system.

---

168. NO TRUSTED-DEVELOPER ASSUMPTION

MaanyaOS privacy architecture is not intended to require users to blindly trust the developer with their encryption keys where the implementation does not provide such access.

---

169. ARCHITECTURAL ACCESS BOUNDARY

Where encryption keys are generated and retained exclusively under user or device control, MaanyaOS infrastructure may not possess the information required to decrypt the protected content.

---

170. IMPLEMENTATION DEPENDENCY

The preceding statement applies only where the actual implementation maintains that architectural separation.

---

171. NO FALSE PRIVACY CLAIMS

MaanyaOS shall not claim that data is inaccessible to MaanyaOS if a deployed service actually possesses the required decryption material.

---

172. TRANSPARENCY

Security documentation should identify whether cryptographic operations occur:

- locally;
- remotely;
- through hardware;
- through third-party services; or
- through a combination of these mechanisms.

---

173. USER VERIFICATION

Where practical, users should be able to inspect relevant security configuration and determine whether external services participate in key management.

---

174. PRIVACY BY DEFAULT

Where technically feasible, MaanyaOS may select configurations that minimize unnecessary external access to protected information.

---

175. PRIVACY BY DESIGN

Privacy may be incorporated into MaanyaOS architecture rather than treated solely as a post-deployment policy.

---

176. DATA MINIMIZATION

MaanyaOS may minimize collection and transmission of sensitive information where doing so is technically feasible.

---

177. NO UNNECESSARY KEY TRANSMISSION

MaanyaOS should not transmit private encryption keys merely for convenience where local operation is technically sufficient.

---

178. KEY ESCROW DISCLOSURE

Any future MaanyaOS service implementing key escrow should clearly disclose that architecture and its applicable terms.

---

179. ENTERPRISE KEY MANAGEMENT

Enterprise editions may support organization-controlled key management.

Such functionality may be governed by separate enterprise terms.

---

180. USER VERSUS ORGANIZATION CONTROL

In managed environments, encryption keys may be controlled by an organization rather than an individual user.

---

181. ORGANIZATIONAL ACCESS

Where an organization controls encryption keys, the organization's authorized administrators may potentially access protected data according to its security architecture and applicable law.

---

182. PERSONAL DEVICE

On personally controlled devices, encryption credentials may remain under the user's control.

---

183. SHARED DEVICES

Shared devices may require additional access-control policies.

---

184. FAMILY OR MULTIUSER SYSTEMS

Multiple users may have different permissions to protected information.

---

185. USER SEPARATION

MaanyaOS may provide per-user storage and permission boundaries.

---

186. PRIVATE USER DIRECTORIES

User directories may be protected through filesystem permissions and encryption mechanisms.

---

187. ROOT LIMITATION

Encryption does not necessarily prevent a privileged administrator from observing data after it has been decrypted and made available to the operating system.

---

188. OFFLINE ATTACKS

Full-disk encryption may reduce the usefulness of a stolen powered-off storage device to an attacker lacking the required credentials or keys.

---

189. ONLINE ATTACKS

Full-disk encryption does not automatically prevent attacks against a running and unlocked system.

---

190. LOCKED DEVICE

Locking a device may reduce casual unauthorized access but does not replace full-disk encryption.

---

191. POWERED-OFF DEVICE

Encryption may provide stronger protection against certain offline attacks when the device is powered off and properly configured.

---

192. THREAT MODEL

Security guarantees should always be interpreted according to the relevant threat model.

---

193. FINAL PRIVACY PRINCIPLE

«MaanyaOS is designed to protect user data without unnecessarily requiring the MaanyaOS developer to possess the user's encryption keys.»

---

194. FINAL KEY PRINCIPLE

«If the user alone controls the required encryption key and the architecture provides no recovery escrow, loss of that key may mean loss of access to the protected data.»

---

195. FINAL TPM PRINCIPLE

«TPM 2.0 may strengthen platform-bound key protection, but it is not a guarantee against every hardware, firmware, software, or physical attack.»

---

196. FINAL VERACRYPT PRINCIPLE

«VeraCrypt compatibility is interoperability; it is not ownership of VeraCrypt.»

---

197. FINAL AES PRINCIPLE

«AES-256 is a cryptographic primitive, not a complete security system.»

---

198. FINAL DATA PRINCIPLE

«Encryption reduces unauthorized disclosure risk; it does not eliminate the need for backups, secure configuration, trusted software, and responsible credential management.»

---

199. THIRD-PARTY LICENSE PRIORITY

Third-party cryptographic software, TPM components, VeraCrypt, LUKS, dm-crypt, OpenSSL, libsodium, Linux, firmware, hardware technologies, and related components remain governed by their respective licenses and rights.

---

200. OPEN-SOURCE LICENSE PRIORITY

Nothing in this License overrides rights or obligations that cannot lawfully be restricted under an applicable Open-Source license.

---

201. PROPRIETARY MAANYAOS TECHNOLOGY

Original MaanyaOS cryptographic orchestration, privacy architecture, integration code, configuration systems, interfaces, tooling, and security infrastructure may be protected under applicable MaanyaOS proprietary licensing.

---

202. GOVERNING LAW

This License shall be interpreted subject to applicable law.

To the extent legally permissible, disputes concerning original proprietary MaanyaOS technology shall be subject to courts having competent jurisdiction in Delhi, India.

Nothing in this clause grants jurisdiction to a court that otherwise lacks lawful jurisdiction.

---

203. SEVERABILITY

If any provision is found unenforceable, the remaining provisions shall remain effective to the extent permitted by applicable law.

---

204. LEGAL REVIEW

This document is a licensing template for the MaanyaOS project and should be reviewed by a qualified legal professional before being relied upon as an enforceable commercial agreement.

---

205. FINAL OWNERSHIP STATEMENT

Copyright © 2026 Kriday Ghosh.

All Rights Reserved with respect to original proprietary MaanyaOS technology, subject to applicable third-party rights and Open-Source licensing obligations.

END OF LICENSE