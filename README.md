# Become a Member - Cloud Native Security Pakistan (CNSP)

Welcome to **Cloud Native Security Pakistan (CNSP)**! We are a community-driven organization focused on advancing cloud-native security practices, open source adoption, and security innovations aligned with CNCF (Cloud Native Computing Foundation) principles.

## 🎯 Our Mission

CNSP is dedicated to:
- **Cloud-Native Security**: Building secure, scalable, and resilient cloud-native applications using CNCF technologies
- **Open Source Adoption**: Promoting and contributing to open source security tools and projects
- **CNCF Alignment**: Following CNCF best practices and working with CNCF projects (Kubernetes, Prometheus, Falco, OPA, and more)
- **Security Best Practices**: Implementing security controls and practices for cloud-native environments
- **Community Building**: Fostering collaboration and knowledge sharing among security professionals

## 🚀 How to Join

Becoming a member of CNSP is simple and automated! Follow these steps:

1. **Open an Issue**: Click on the [Issues](https://github.com/Cloud-Native-Security-Pakistan/become-a-member/issues) tab and create a new issue using the "Request Invitation" template.

2. **Fill Out the Template**: 
   - Provide your GitHub username
   - Tell us why you want to join CNSP

3. **Automated Invitation**: Our GitHub Actions workflow will:
   - Automatically extract your username from the issue
   - Send you an invitation to join the organization
   - Add you to the **Newbie** team (your starting team)
   - Post a welcome comment with next steps

4. **Accept the Invitation**: Check your email or GitHub notifications and accept the invitation to become a member of this organization this way you will be added to team newbies!

5. **Complete Member Registration** (Choose one method):
   
   **Option A: GitHub PR Method (Recommended - Earn Extra Points! ⭐)**
   - Create a file in the `/membersmap` directory with your GitHub username
   - Add your information (name, location, interests, etc.)
   - Submit a Pull Request to add yourself to the member map
   - **Bonus**: You'll earn extra points for submitting via PR!
   - An admin will review and merge your PR, then promote you to **Member** team
   
   **Option B: Google Form Method**
   - Fill out the [CNSP Member Registration Form](YOUR_GOOGLE_FORM_LINK)
   - Your information will be added to our database and appear on the website member map
   - An admin will review and promote you to **Member** team

6. **Start Contributing**: Once you're a **Member**, you can start contributing to projects and advance to **Contributor**!

---

**Ready to join?** [Request an invitation now!](https://github.com/Cloud-Native-Security-Pakistan/become-a-member/issues/new?template=invite.yml)

## 👥 Team Structure & Progression

CNSP uses a tiered team structure that gamifies contribution and recognizes your growth:

### 🟢 Newbie (Entry Level)
- **Starting Team**: All new members join here automatically
- **Requirements**: Just join the organization!
- **Permissions**: Basic access to organization repositories
- **Next Step**: Complete the member onboarding form!

### 🔵 Member
- **Promotion Trigger**: Choose one of two methods:
  
  **Method 1: GitHub PR (Recommended - Earn Extra Points! ⭐)**
  - Create a file in the `/membersmap` directory with your GitHub username
  - Add your information (name, location, interests, etc.) to the file
  - Submit a PR to add yourself to the member map
  - **Bonus**: You get extra points for submitting via PR and learning GitHub workflow!
  - Admin reviews and merges your PR
  
  **Method 2: Google Form**
  - Fill out the [CNSP Member Registration Form](YOUR_GOOGLE_FORM_LINK)
  - Your information is added to our database and appears on the website member map
  - Admin reviews and approves your submission
  
- **Requirements**:
  - **GitHub Method**: Create a file named `YOUR_USERNAME.md` (or `YOUR_USERNAME.json`) in the `/membersmap` directory with your details
  - **Form Method**: Complete the Google form with your information
  - Wait for admin review and approval (usually within 24-48 hours)
- **Benefits**: 
  - Official member status
  - Listed in the community member map (on website)
  - Access to member-only channels and resources
  - Your profile visible to the community
  - **GitHub PR method**: Extra contribution points for your first PR!
- **Next Step**: Make your first contribution!

### 🟡 Contributor
- **Promotion Trigger**: 
  - Your first PR is merged, OR
  - An admin adds the `contributor` label to your PR/issue
- **Benefits**: 
  - Recognition for your first contribution
  - Access to contributor-only resources
- **Next Step**: Keep contributing to advance!

### 🟠 Advanced Contributor
- **Promotion Trigger**:
  - Multiple PRs merged (typically 3-5 quality contributions), OR
  - Consistent contributions over time, OR
  - Admin adds the `advanced-contributor` label
- **Benefits**:
  - Enhanced repository access
  - Priority in discussions and events
  - Mentorship opportunities
- **Next Step**: Become a mentor!

### 🔴 Mentor/Admin
- **Promotion Trigger**: 
  - Hand-picked by organization admins
  - Demonstrated leadership and expertise
  - Active mentorship of other members
- **Benefits**:
  - Administrative privileges
  - Ability to review and approve contributions
  - Lead community initiatives

## ⚙️ How the Automated Workflows Work

### 1. Onboarding Workflow (`invite.yml`)

**Trigger**: When a new issue is created with the `invite-request` label

**What it does**:
1. Extracts your GitHub username from the issue body
2. Looks up your user account
3. Sends an organization invitation
4. **Automatically adds you to the "Newbie" team** (default entry team)
5. Posts a welcome comment with community links and next steps

**Requirements**:
- Issue must use the "Request Invitation" template
- Template automatically adds the `invite-request` label

### 2. Member Promotion Workflow (`member-promotion.yml`)

**Trigger**: 
- When a PR is merged that adds a file to the `/membersmap` directory

**What it does**:
1. Detects that a file was added to `/membersmap` directory
2. Identifies the PR author
3. Checks if user is in the "Newbie" team
4. **Automatically promotes user from "Newbie" to "Member" team**
5. Removes user from "Newbie" team (if applicable)
6. Posts a congratulations comment with next steps

**Note**: This workflow only runs for PRs that add files to `/membersmap/`. Users who use the Google form method will be manually promoted by admins.

### 3. Contributor Promotion Workflow (Coming Soon)

**Trigger**: 
- When a PR is merged (non-membersmap), OR
- When a promotion label is added (`contributor`, `advanced-contributor`)

**What it does**:
1. Identifies the PR author
2. Checks their current team membership
3. Determines the appropriate next team based on:
   - Number of merged PRs
   - Labels on the PR
   - Admin decisions
4. Moves the user to the new team
5. Posts a congratulations comment

**Promotion Logic**:
- **Newbie → Member**: 
  - Add yourself to `/membersmap` directory via PR (automatic promotion), OR
  - Fill out Google form (manual admin promotion)
- **Member → Contributor**: First PR merged OR `contributor` label
- **Contributor → Advanced Contributor**: 3+ PRs merged OR `advanced-contributor` label
- **Advanced Contributor → Mentor/Admin**: Admin decision only

## 📋 Workflow Details

### Onboarding Process Flow

```
User creates issue → Workflow triggered → Username extracted → 
Invitation sent → Added to "Newbie" team → Welcome comment posted → Issue closed
```

### Promotion Process Flow

```
PR merged / Label added → Workflow triggered → User identified → 
Current team checked → Promotion logic applied → Team updated → 
Congratulations comment posted
```

## 🎁 Benefits of Being a Member

As a CNSP member, you'll enjoy:

- 🚀 **Access to Labs & Projects**: Participate in hands-on security labs and real-world projects using CNCF technologies
- 🤝 **Community Collaboration**: Connect with like-minded security professionals and contribute to open source projects
- 📚 **Learning Resources**: Access to curated resources, CNCF documentation, and cloud-native security best practices
- 🎯 **Open Source Contribution**: Opportunities to contribute to and adopt open source security tools
- 💡 **Knowledge Sharing**: Contribute to and learn from community discussions on cloud-native security
- 🏆 **CNCF Ecosystem**: Engage with CNCF projects and align with industry-standard practices
- 🎮 **Gamified Progression**: Clear path from Newbie to Mentor with recognition at each level

## 🔗 Join Our Community

🎯 **CNCF Bevy Chapter**: [Join our CNCF Community](https://community.cncf.io/cloud-native-security-pakistan/) - Connect with 257+ members, attend events, and participate in discussions

📱 **WhatsApp Community**: [Join our WhatsApp Community](https://chat.whatsapp.com/F5Hf1ZwI22TK6EcV6zz4wo) - Connect with members, get updates, and participate in discussions

🌐 **Social Media**:
- [LinkedIn](https://www.linkedin.com/company/cloud-native-security-pakistan) - Follow us for updates and announcements
- [Twitter/X](https://twitter.com/cnspk) - Stay updated with the latest news
- [GitHub Organization](https://github.com/Cloud-Native-Security-Pakistan) - Explore our projects and repositories

## 🛠️ Technical Details

### Required Secrets

For the workflows to function, the following secrets must be configured:

- **`ORG_INVITE_TOKEN`**: GitHub Personal Access Token with `admin:org` scope
  - Used for inviting users and managing team memberships
  - Can be set at organization or repository level

- **`DEFAULT_TEAM_ID`** (Optional): Numeric ID of the "Newbie" team
  - If not set, users will be direct members (not recommended)
  - Get team ID from: `https://api.github.com/orgs/Cloud-Native-Security-Pakistan/teams`

- **`DEFAULT_TEAM_NAME`** (Alternative): Name of the "Newbie" team (e.g., "Newbie")
  - Workflow will automatically look up the team ID
  - Less reliable than using team ID directly

### Workflow Files

- **`.github/workflows/invite.yml`**: Handles automatic invitations and team assignment
- **`.github/ISSUE_TEMPLATE/invite.yml`**: Issue template for membership requests
- **`.github/dependabot.yml`**: Keeps GitHub Actions dependencies updated

### Team Configuration

Teams should be created in the organization with the following names:
- `Newbie` (or `newbie`) - Entry level team (automatic on join)
- `Member` (or `member`) - After completing registration form and map
- `Contributor` (or `contributor`) - First contribution level
- `Advanced Contributor` (or `advanced-contributor`) - Second promotion level
- `Mentor/Admin` (or `mentor-admin`) - Highest level (admin-managed)

## 📝 Contributing

We welcome contributions! Whether it's:
- Improving documentation
- Adding new labs or projects using CNCF technologies
- Contributing to open source security tools
- Sharing cloud-native security best practices
- Reporting issues or suggesting features

Please open an issue or submit a pull request. We follow CNCF's contribution guidelines and welcome contributions from the community.

## 📄 License

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ❓ FAQ

**Q: How long does it take to get invited?**  
A: The invitation is sent automatically within seconds of creating the issue. Check your email or GitHub notifications.

**Q: What if I don't receive the invitation?**  
A: Check the issue comments for any error messages. If there's an issue, comment on the issue and an admin will help.

**Q: Can I skip the Newbie team?**  
A: No, all new members start in the Newbie team. This ensures everyone has a consistent onboarding experience.

**Q: How do I become a Member?**  
A: You have two options:
1. **GitHub PR Method (Recommended)**: Create a file in the `/membersmap` directory with your GitHub username (e.g., `yourusername.md` or `yourusername.json`). Add your information and submit a PR. **You'll earn extra points for this method!**
2. **Google Form Method**: Fill out the [CNSP Member Registration Form](YOUR_GOOGLE_FORM_LINK). Your info will be added to our database and appear on the website map.

Both methods require admin approval. Once approved, you'll be promoted to the Member team.

**Q: Why should I use the GitHub PR method?**  
A: The GitHub PR method earns you extra contribution points because you're:
- Learning the GitHub workflow
- Making your first PR
- Getting familiar with the contribution process
- This PR counts toward your Contributor promotion!

**Q: What information should I include in my member map file?**  
A: Include your name, location, interests, GitHub profile link, and how you'd like to contribute. Check existing files in `/membersmap` for examples of the format.

**Q: What format should I use for my member map file?**  
A: You can use Markdown (`.md`) or JSON (`.json`) format. Check the `/membersmap` directory for examples and templates.

**Q: Will my information appear on the website?**  
A: Yes! Whether you use the GitHub PR method or Google form, your information will be added to our database and displayed on the CNSP website member map.

**Q: How do I get promoted?**  
A: Start contributing! Make PRs, help with issues, and engage with the community. Promotions happen automatically when PRs are merged or when admins recognize your contributions.

**Q: What if I think I should be promoted but haven't been?**  
A: You can discuss this with admins in the community channels, or an admin can manually add promotion labels to recognize your contributions.

---

**Ready to start your journey?** [Request an invitation now!](https://github.com/Cloud-Native-Security-Pakistan/become-a-member/issues/new?template=invite.yml)
