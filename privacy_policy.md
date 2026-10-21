# Test Studio Privacy Policy

**Effective date:** 21 October 2026

This policy explains what information the Test Studio desktop application ("Test Studio", "the app") handles, where
it is kept, and who it is shared with. Test Studio is provided by Ashokkumar T.A. ("we", "us"). Questions about this
policy: [ashokkumar.ta@gmail.com](mailto:ashokkumar.ta@gmail.com).

## In short

- Everything you create in Test Studio is stored **only on your computer**.
- Test Studio has **no telemetry, analytics, advertising or crash reporting**, and it doesn't check for updates. We
  don't receive your requests, responses, collections or anything else you work on.
- The **full edition** asks you to sign in once with Google, through the sign-in service **Auth0**. Signing in shares
  your name and email address with Auth0 and records that you signed in.
- The **demo edition** doesn't sign you in. The name and email you type into it stay on your computer.

## 1. Information stored on your computer

Test Studio keeps the following in its data folder on your computer (`%APPDATA%\ancr` on Windows,
`~/Library/Application Support/ancr` on macOS):

- **Your work:** workspaces, collections, requests, connections, environments and their variables, scripts, test
  data, baselines and reports you save.
- **History:** the requests you have sent and the responses they received, up to the limits you set in Settings.
- **Cookies** that servers set in responses to your requests, and **OAuth 2.0 tokens** obtained for your requests.
- **Settings:** your theme, network and proxy settings, and similar preferences.
- **The vault:** secrets you choose to keep there, encrypted with your computer login (Windows DPAPI or the macOS
  Keychain, where available).
- **Who uses the app:** your name and email address, and, in the full edition, your Auth0 user ID and when you signed
  in. This is encrypted with your computer login where available. It is printed on the reports you save ("Run by Name
  (email)").

We have no access to any of this. It stays on your computer until you delete it, sign out (which deletes who uses the
app), or uninstall Test Studio and delete its data folder. Files you export, and reports you save, go wherever you
save them, and you decide who to share them with.

## 2. Information shared when you sign in (full edition)

When you click **Continue with Google**, your web browser opens the sign-in page of Auth0 (operated by Okta, Inc.),
which passes you on to Google:

- **Google** asks you to sign in to your Google account and to allow Test Studio to see your name, email address and
  basic profile. Google's handling of your account is covered by the
  [Google Privacy Policy](https://policies.google.com/privacy).
- **Auth0** receives your name, email address, whether your email address is verified, your basic Google profile
  (such as your profile picture), and technical details of each sign-in such as its date and time, your IP address and
  your browser. It keeps a user record so that we can see who has signed in, when they first signed up, when they last
  signed in and how many times. Auth0's handling is covered by the [Okta Privacy Policy](https://www.okta.com/privacy-policy/).
  Our Auth0 tenant is hosted in the United States.
- **Test Studio** receives your name, email address and Auth0 user ID, and keeps them on your computer as described
  above. It keeps no passwords, and it doesn't keep the sign-in tokens.

We use this information only to know who uses Test Studio, to show it on the reports you save, and to contact you
about Test Studio if needed. We don't sell it, and we don't use it for advertising.

You stay signed in until you choose **⚙ → Sign out**. Signing out deletes who uses the app from your computer; it
doesn't delete your Auth0 user record (see section 5).

## 3. Connections Test Studio makes

Test Studio connects to the network only:

- to the servers, APIs, brokers and MCP servers **you** send requests to or connect to, with the data you put in those
  requests (including any authentication you configure);
- to Auth0 and Google when you sign in to the full edition;
- through your web browser, when you open a link such as **Help** (the user guide on GitHub), or sign in to an OAuth
  2.0 provider for a request.

The sample workspace, if you include it, contains requests to public test services; they are sent only when you send
them. What those services, and any other server you send requests to, do with the data is up to them.

## 4. Children

Test Studio is a tool for software professionals. It is not directed at children, and we don't knowingly collect
information from anyone under 16.

## 5. Your choices and rights

- You can view, change or delete everything in section 1 in Test Studio itself, or by deleting its data folder.
- You can ask us for a copy of the information Auth0 holds about you, ask us to correct it, or ask us to delete your
  Auth0 user record, by emailing [ashokkumar.ta@gmail.com](mailto:ashokkumar.ta@gmail.com) from the email address you
  signed in with. Once it is deleted, you will need to sign in again to use the full edition.
- You can remove Test Studio's access to your Google account at any time in your
  [Google Account settings](https://myaccount.google.com/permissions).

Depending on where you live, you may have further rights over your personal information, such as to object to its
use or to complain to a data protection authority. Contact us to use them.

## 6. Security

Information on your computer is protected by your computer's own security, with the vault and who uses the app
encrypted with your computer login where your system supports it. Sign-in uses the OAuth 2.0 authorization code flow
with PKCE over HTTPS. No method of storage or transmission is completely secure, so keep your computer and accounts
protected.

## 7. Changes to this policy

We may update this policy, for example when Test Studio changes what it does. The current version is published with
each release at [github.com/ashokkumarta/test-studio](https://github.com/ashokkumarta/test-studio), with its effective
date at the top.

## 8. Contact

Ashokkumar T.A. · [ashokkumar.ta@gmail.com](mailto:ashokkumar.ta@gmail.com)
