#### Description

[RETAILER-XXXX](https://ordermentum.atlassian.net/browse/RETAILER-XXXX)
[SUPPLIER-XXXX](https://ordermentum.atlassian.net/browse/SUPPLIER-XXXX)

**Overview**
*Provide a clear, concise summary of the purpose and impact of these changes.*

----
#### PR Type

_Check one or more and add the corresponding number of reviewers_

- [ ] Bugfix or minor change _(1)_
- [ ] Feature _(2)_
- [ ] Breaking change (existing functionality no longer works as expected) _(2)_
- [ ] Critical impact (security, payments or critical functionality) _(2+CTO)_


----
#### Changes

_List the main changes in this PR. Include screenshots if necessary._

----
#### Testing
**Acceptance Criteria**
- *Explicitly list measurable conditions that validate the implementation*
- *Include specific scenarios or edge cases tested*


**Test Coverage**
- [ ] Unit tests added/updated
- [ ] Integration tests added/updated
- [ ] E2E tests added/updated
- [ ] Manual testing completed

----

#### Checklist
**Code Quality**
- [ ] No commented-out code
- [ ] Appropriate logging added
- [ ] No hardcoded credentials/secrets

**Functionality**
- [ ] Tested with non-admin user
- [ ] Works across different user roles
- [ ] Backward compatibility maintained

**Deployment Readiness**
- [ ] Rebased against latest `develop` branch
- [ ] Feature flag implemented (if new feature)
- [ ] Database migrations reviewed
- [ ] Can be safely released to production

**Security**
- [ ] Input validation implemented
- [ ] Proper error handling
- [ ] No exposed sensitive information
- [ ] Follows least privilege principle

**Performance**
- [ ] No unintended performance regressions
- [ ] Benchmarks/profiling performed if applicable
