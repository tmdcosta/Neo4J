# Member status

This article sidplays the possible status for each item (member photo, member, consent and document).

**The possible status per item are:**
- **MemberStatus:** NEW, ACTIVE, INACTIVE, BLOCKED, EXPIRED, DELETED
- **MemberPhotoStatus:** AVAILABLE, NOT_AVAILABLE
- **MemberConsentStatus:** AVAILABLE, NOT_AVAILABLE, OUTDATED, EXPIRED
- **MemberDocumentStatus:** AVAILABLE, NOT_AVAILABLE, EXPIRED

<!-- theme: info -->

> #### In order for a member to be successfully enrolled in the system, they must have the following statuses:
>- **Member Status:** ACTIVE
>- **Member Photo Status:** AVAILABLE
>- **Member Consent Status:** AVAILABLE
>- **Member Document Status:** AVAILABLE
****


### Status description
**Member Status:**
- **NEW:** The member is new, and has not begin enrollment.
- **BLOCKED:** The member has begun enrollment, but has not enabled their biometric account.
- **ACTIVE:** The member has enabled their biometric account, but may or may not have completed their enrollment.
- **INACTIVE:** The member’s account has been disabled due to inactivity.
- **EXPIRED:** The member’s enrollment has expired because of their consent or document status expiring.
- **DELETED:** The member’s account has been deleted.

**Member Photo Status:**
- **AVAILABLE:** The member has a valid photo.
- **NOT_AVAILABLE:** The member does not have a valid photo.

**Member Consent Status:**
- **AVAILABLE:** The member has provided their consent & it is not expired or outdated.
- **NOT_AVAILABLE:** The member has not provided their consent.
- **OUTDATED:** The consent and terms of use that the member accepted are no longer in effect, the member must accept a newer version of the terms of use.
- **EXPIRED:** The duration of the member’s consent has reached its end, and the member must extend their consent expiration date.

**Member Document Status:**
- **AVAILABLE:** The member has provided their ID, it is in the system and it is not expired.
- **NOT_AVAILABLE:** The member does not have their ID in the system.
- **EXPIRED:** The member’s ID is expired.
