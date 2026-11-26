# Ballast Privacy Policy

**Effective date: November 26, 2026**

Ballast is a portfolio backtesting app for Windows that runs on your own computer. This policy explains what
information is collected when you use Ballast, why, who handles it, and the choices you have. "We", "us" and
"the developer" mean the independent developer of Ballast. "You" means the person using Ballast.

**The short version:** your portfolios, backtests, results and settings stay on your PC and are never sent to us.
To give you an account, we keep your username, email address and a few account details. We don't sell or share
your information, and we don't use advertising or tracking.

## 1. What stays on your computer

Ballast does its work locally. The following are stored only in your Windows user folder (`%APPDATA%\Ballast`)
and are **never sent to us**:

- your portfolios, glidepaths, settings and theme
- backtest results, saved backtests, forecasts and logs
- the market-data cache
- your conversations with the AI assistant (see section 4)
- your Gemini API key, if you choose to add one

Uninstalling Ballast keeps this folder so you don't lose your work. Delete the folder yourself to remove it.

## 2. What we collect for your account

When you create an account and use Ballast, we store:

| Information | Why |
|---|---|
| Username | To identify your account and let you sign in with it |
| Email address | Sign-in, the 6-digit verification code, password resets, and important account or service messages |
| Account ID (a random identifier from our sign-in provider) | To link your sign-in to your account |
| Sign-in method (password or Google) | To support the way you sign in |
| Password | **We never see or store your password.** It's handled by Google Firebase Authentication, which stores it in a scrambled, one-way (hashed) form |
| Name and email from Google, if you choose "Continue with Google" | To create and sign in to your account. We don't receive your Google password or access to anything else in your Google account |
| Date you joined, last sign-in time, number of sign-ins, app version | To run the service, help with problems and understand how many people use which version |
| Your plan (Free, Pro, Lifetime) | To unlock the features you're entitled to |
| Device ID, **only for paid or lifetime plans** | A one-way fingerprint derived from your Windows installation's ID, used to keep a Pro plan on one PC. It can't be turned back into the original ID and doesn't identify you or your hardware by itself |
| A log of account events (sign-up, code sent, email verified, Pro moved to another PC) | Security, preventing abuse and fake accounts, and troubleshooting |
| Feedback and reviews you choose to send, with your rating | To read and respond to your feedback and improve Ballast |

Each time Ballast checks your account (about every 6 hours while you're online), it sends your account token, the
device ID and the app version, so your plan and device lock can be confirmed.

We don't collect your name (unless Google provides it at Google sign-in), address, phone number, payment card
details, portfolio contents, trading accounts or browsing history.

## 3. Who handles your information (service providers)

We use a small number of services to run Ballast. They process information on our behalf and under their own
privacy terms:

- **Google Firebase Authentication:** stores accounts and passwords and handles sign-in, including Google sign-in.
- **Google Apps Script, Google Sheets and Gmail:** run our account service, store the account list and feedback,
  and send verification-code emails. Ballast emails come from the developer's Google account.
- **GitHub (Microsoft):** hosts the Ballast download page and updates. When Ballast checks for or downloads an
  update, your computer connects to GitHub, which can see your IP address.
- **Yahoo Finance:** price data is downloaded **directly from your computer**, not through us. Yahoo can see your IP
  address and which tickers are requested, under Yahoo's own terms.
- **Payment provider (when paid plans launch):** payments will be handled by a third-party provider such as Lemon
  Squeezy or Gumroad. We will never receive or store your full card details. This policy will be updated to name the
  provider before paid plans are offered.

Google, GitHub and these providers may log technical information such as IP addresses when your computer
connects to them. We don't use these logs to track you.

## 4. The AI assistant

- **Ollama (default):** runs entirely on your PC. Your messages never leave your computer.
- **Gemini (optional):** if you switch the assistant to Gemini, your messages and portfolio list are sent to
  **Google** using **your own** API key, under Google's Gemini API terms. On Google's free tier, Google may use the
  content to improve its products. Don't include private information.

## 5. How we use your information

We use account information only to:

- create and secure your account, verify your email and prevent fake or automated accounts
- provide the features of your plan and enforce the one-PC rule for paid plans
- send service messages, such as codes, password resets and important changes to Ballast or these policies
- respond to feedback and support requests, and improve Ballast
- comply with the law and protect the rights and safety of users and the developer

We **do not** sell your personal information, share it for advertising, or use it for advertising or profiling. We
will only send marketing emails if you have opted in, and every such email will include a way to stop them.

## 6. How long we keep it

- **Account information:** kept while your account exists. If you ask us to delete your account, we delete it from
  our account service and sign-in provider within 30 days.
- **Accounts that never verify their email:** may be deleted at any time.
- **Feedback:** kept until it is no longer useful or you ask us to delete it.
- **Event logs:** kept for up to 24 months for security, then deleted.
- Some information may remain briefly in backups held by our providers, and we may keep information longer
  where the law requires it.

## 7. Your choices and rights

You can:

- **See** the account information we hold about you
- **Correct** it
- **Delete** your account and its information
- **Get a copy** of it
- **Object to** or **limit** how we use it, where the law gives you that right

To ask for any of these, use **Settings → Account → 💬 Feedback & reviews** in Ballast with the type "Question", or
reply to any email from Ballast. We may need to confirm that the request comes from the account holder. We'll
respond within 30 days, or sooner if your local law requires it. Depending on where you live, you may also have
the right to complain to a data protection authority.

You can stop using Ballast at any time. Your local data stays on your PC unless you delete it.

## 8. Security

Passwords are handled by Google Firebase and never stored by us. All connections to our account service use
encrypted HTTPS. Account sessions on your PC are digitally signed so they can't be altered. Access to the
account list is limited to the developer. No system is completely secure, so use a strong, unique password and
keep your PC protected.

## 9. Children

Ballast is intended for adults and is not directed at children. You must be at least **18 years old** (or the age of
majority where you live) to create an account. If we learn that a child has created an account, we will delete it.

## 10. International users

Our service providers may store and process information in the United States and other countries. Those countries
may have different data protection laws from yours. By using Ballast, you understand that your account
information is processed there.

## 11. Changes to this policy

We may update this policy, for example when paid plans launch. We'll change the effective date above, and for
significant changes we'll tell you in the app or by email before they take effect. Continuing to use Ballast after
the effective date means you accept the updated policy.

## 12. Contact

For questions about this policy or your information, send a message from **Settings → Account → 💬 Feedback &
reviews** in Ballast, or reply to any email from Ballast.
