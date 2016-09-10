# GTAP Asset Definition

TAPP Guild Coins are claims against the TAPP Guild Treasury. The usual way GTAP is created is by earning XP. GTAP are earned 1:1 with XP.

GTAP may be issued for reasons other than earning, without XP. For istance, GTAP issued as a reimbursement for expenses do not deserve XP. These cases are voted on individually.

### Roles

 + Member
 + Service Provider

All TAPP Guild members are peers in the GTAP network. Any member may unilaterally transfer their GTAP to another by submitting a signed entry to the ledger. Members may redeem earned GTAP at a penalty of 1% per day from the day of the request, subject to fees and availability.

##### Member Withdrawal Table

To help explain the member withdrawals, this actuary table shows the expected yield assuming a hypothetical GTAP price of 1 chicken (CHKN).

| Days since request | Penalty | GTAP Redeemed | Yield |
|--------------------|---------|--------------|-------|
| 0 | 100% | 1 | 0 CHKN |
| 1 | 99% | 1 | 0.01 |
| 2 | 98% | 1 | 0.02 |
| 3 | 97% | 1 | 0.03 |
| n (< 100) | (100 - n)% | 1 | n / 100 |
| 100 | 0% | 1 | 1 |

Service Providers are outside of the TAPP Guild, and unable to receive payment in GTAP. As such, they are not subject to time penalties, and may receive Treasury withdrawals immediately.

### Funds

Funds may be established by contract, to hold assets on behalf of the Treasury. These may elect cosigners to manage assets only with 90% approval, as per the Change Treasury Sign Policy.

Funds may charge up to 1% for withdrawal processing.

### Revenue

At founding, this guild received only $1 from the parent Treasury.

This guild will offer support and possibly other services to TAPP users. Details to be arranged in later contracts.

### Sponsorships

For every 1 non-sponsorship GTAP issued, an additional 1% GTAP will be issued and allocated to the Git Guild Treasury. For instance, if 2.2 GTAP are issued to a member, 0.022 GTAP are to be issued to the Git Guild Treasury.

##### Sponsorship Table

| Name | Recipient | Asset | Percent on Issue |
|------|-----------|-------|------------------|
| Git Guild | FX:GTAP:GitGuild | GTAP | 1% |
