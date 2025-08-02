# Website - Agentics Meeting Summary

**Date:** July 30, 2025  
**Duration:** 59 minutes  
**Meeting ID:** 01K0YEVQQ0W0QJZQC52T3PCQGR  

## Attendees
- **Martin Cleaver** - Technical lead
- **Brad Ross** - Project coordinator  
- **Nick Ruest** - Content creator
- **rUv** - Strategic lead
- **Mat** - Development/onboarding

## Executive Summary

This meeting focused on the final preparations for migrating the Agentics community platform from the current native application to a new Disco-based system. The team discussed technical integrations, user migration strategies, content organization, and launch timeline. Key decisions were made regarding legacy user management and content strategy to ensure a smooth transition while maintaining existing paid subscriptions.

## Key Decisions & Outcomes

### 🎯 **Migration Strategy - "OG Group" Solution**
- **Decision:** Create a legacy user group ("OG") for existing ~120 paid subscribers
- **Implementation:** Legacy users continue paying through old Stripe system while getting free access on new platform
- **Timeline:** Brad Ross to implement starting at 2 PM same day
- **Benefit:** Zero disruption to existing paying customers, no payment re-authorization required

### 🚀 **Launch Readiness Assessment**
- **Status:** Platform ready for soft launch with 43 existing test users
- **Content:** 5 courses completed by Nick, ready for premium tier
- **Technical:** Stripe integration complete, onboarding system functional

### 📊 **Content Strategy Framework**
- **Free Tier:** Kaltura "Ask Me Anything" searches with keyword-based content
- **Premium Tier:** Structured courses and exclusive content
- **Strategy:** Use content access as primary conversion driver for paid memberships

## Technical Integrations

### Google Analytics Setup
- **Requirement:** Google Analytics ID needed for both Disco and main website
- **Contact:** Ron or LeAndrew identified as holders of credentials
- **Implementation:** Simple JavaScript token addition for Disco platform

### Kaltura Video Integration
- **Success:** Direct embedded links tested and working
- **Functionality:** Videos open in new tabs when clicked
- **Content Strategy:** Keyword-based searches to quickly populate 25+ content pieces across membership tiers

### User Onboarding Flow
- **Questions:** Minimized to essential data only
  - Name and contact information
  - Physical location (city/country) for chapter organization
  - Participation preferences (accreditation, volunteering, networking, etc.)
  - Expectations and feedback field

## Action Items by Assignee

### **Brad Ross**
- [x] Download user list from Supabase for OG member setup (Started 2 PM)
- [ ] Create legacy user group for 120+ existing subscribers
- [ ] Test keyword-based Kaltura content sections across membership tiers

### **Nick Ruest**
- [ ] Add Denver chapter to chapters page by linking created product
- [x] Publish five completed courses under premium section
- [ ] Continue creating additional courses (target: 12 total courses)

### **Mat**
- [ ] Finalize onboarding system completion and add remaining improvements
- [ ] Create content and tutorials once content plan is established

### **rUv**
- [ ] Update main website to redirect dashboard access to community.agentics.org once OG setup complete
- [ ] Strip unnecessary content from landing page and implement login redirect

### **Unassigned**
- [ ] Obtain Google Analytics ID from Ron or LeAndrew
- [ ] Document system ownership details for different website components
- [ ] Invite existing 1,700+ members via CSV import to new platform

## Strategic Developments

### 🤝 **NVIDIA Partnership**
- **Contact:** Jason (Jensen's recruiter) confirmed interest in supporting Agentics
- **Support Areas:** Website development, live casts, marketing activities
- **Status:** Jason and team stepping up after Kelsey's resignation from production crew

### 📈 **Growth Metrics & Projections**
- **Current Membership:** 1,800 active members
- **Luma Events:** ~400 potential additional members
- **Target:** 2,200+ members minimum before major member drive
- **Revenue:** Recent peak day of $714 (six $99/month plan signups)

### 🎓 **Future Accreditation Program**
- **Scope:** Separate from current community platform
- **Standard:** Targeting CPA/Bar Association equivalent difficulty
- **Components:** Ethics, safety, comprehensive technical assessment
- **Funding:** Foundation partnerships and potential grant opportunities

## Content Organization & Moderation

### Chapter Management
- **Local Control:** Chapter moderators manage regional content
- **Admin Oversight:** Full override capabilities for administrators
- **Course Creation:** Restricted to admins unless specifically authorized
- **Multi-language Support:** Critical for non-English speaking chapters

### Content Guidelines
- **Volunteer-Based:** No payment structure for content creators
- **Attribution:** Clear recognition and credit for contributors
- **Quality vs. Quantity:** Focus on valuable content over volume
- **Incremental Approach:** Add content as user base grows to maintain motivation

## Technical Notes

### Platform Limitations
- **Payment Migration:** Cannot transfer Stripe subscriptions between different company structures
- **Integration Gaps:** No official Luma or Disco Zapier integrations
- **Manual Processes:** CSV-based user imports for event attendee conversion

### Workflow Solutions
- **Event Registration:** Luma attendees → Email collection → CSV import → Automatic Disco account creation
- **Content Updates:** Manual addition of Kaltura links and course materials
- **User Management:** Periodic monitoring of legacy payment status

## Timeline & Next Steps

### Immediate (Week of July 30)
1. Complete OG user group implementation
2. Update main website redirect functionality  
3. Begin legacy user migration process

### August 2025
- Complete migration of existing 120+ paid subscribers
- Populate content across membership tiers
- Onboard 1,700+ community members via CSV import

### September 2025
- Launch major member recruitment drive
- Implement merchandise benefits program
- Scale content creation with volunteer contributors

## Meeting Insights

### Key Success Factors
- **Seamless Migration:** OG group solution eliminates payment disruption
- **Content-Driven Growth:** Premium content as primary conversion tool  
- **Community Engagement:** Active member involvement in content creation
- **Strategic Partnerships:** NVIDIA support provides significant resource boost

### Risk Mitigation
- **Legacy Payment Management:** Periodic monitoring prevents abuse of free access
- **Content Quality Control:** Admin approval for course creation maintains standards
- **User Experience:** Simplified onboarding reduces abandonment rates

---

*This summary was generated from Fireflies transcript ID: 01K0YEVQQ0W0QJZQC52T3PCQGR*  
*For detailed conversation flow, refer to the original transcript in Fireflies.*