<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="Learn how PitchUP handles your personal information, privacy choices, and account deletion."
  />
  <meta name="theme-color" content="#111B32" />
  <title>Privacy Policy | PitchUP</title>

  <style>
    :root {
      --navy: #111b32;
      --navy-light: #1e2b46;
      --blue: #208aef;
      --yellow: #f4f537;
      --background: #f7f8fa;
      --white: #ffffff;
      --text: #152039;
      --muted: #59677d;
      --line: #e5e9ef;
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 24px;
    }

    body {
      margin: 0;
      background: var(--background);
      color: var(--text);
      font-family:
        -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, Helvetica, Arial, sans-serif;
      line-height: 1.75;
      -webkit-font-smoothing: antialiased;
    }

    a {
      color: #0964b9;
      text-underline-offset: 3px;
      overflow-wrap: anywhere;
    }

    a:hover {
      text-decoration-thickness: 2px;
    }

    a:focus-visible {
      outline: 3px solid var(--blue);
      outline-offset: 5px;
      border-radius: 3px;
    }

    .skip-link {
      position: absolute;
      top: -80px;
      left: 16px;
      z-index: 10;
      padding: 10px 16px;
      background: var(--yellow);
      color: var(--navy);
    }

    .skip-link:focus {
      top: 16px;
    }

    .hero {
      background: var(--navy);
      color: var(--white);
      padding: 34px 24px 70px;
    }

    .container {
      width: min(100%, 900px);
      margin: 0 auto;
    }

    .brand {
      display: inline-block;
      font-size: 26px;
      font-weight: 900;
      letter-spacing: -1.2px;
      line-height: 1.2;
    }

    .brand span {
      color: var(--yellow);
    }

    .eyebrow {
      margin: 40px 0 10px;
      color: var(--yellow);
      font-size: 12px;
      font-weight: 800;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    h1 {
      margin: 0;
      font-size: clamp(36px, 7vw, 58px);
      line-height: 1.12;
      letter-spacing: -2px;
    }

    .intro {
      max-width: 640px;
      margin: 20px 0;
      color: #c8d2e3;
      font-size: 17px;
    }

    .updated {
      display: inline-block;
      margin: 4px 0 0;
      padding: 7px 12px;
      border: 1px solid #42506a;
      border-radius: 8px;
      color: #d7dfed;
      font-size: 12px;
    }

    main {
      width: min(calc(100% - 32px), 900px);
      margin: -28px auto 48px;
      position: relative;
    }

    .card {
      padding: clamp(24px, 5vw, 48px);
      background: var(--white);
      border: 1px solid var(--line);
      border-radius: 22px;
      box-shadow: 0 12px 35px rgba(17, 27, 50, 0.05);
    }

    .summary {
      padding: 20px;
      border-left: 4px solid var(--blue);
      border-radius: 0 12px 12px 0;
      background: #eef6ff;
      margin-bottom: 28px;
    }

    .summary p {
      margin: 0;
    }

    nav {
      padding-bottom: 28px;
      border-bottom: 1px solid var(--line);
      margin-bottom: 32px;
    }

    nav h2 {
      margin-top: 0;
      font-size: 18px;
    }

    nav ol {
      columns: 2;
      column-gap: 32px;
      padding-left: 22px;
      margin-bottom: 0;
    }

    nav li {
      padding: 4px 0;
      break-inside: avoid;
      font-size: 14px;
    }

    section + section {
      border-top: 1px solid var(--line);
      margin-top: 30px;
      padding-top: 26px;
    }

    h2 {
      color: var(--navy);
      font-size: 23px;
      letter-spacing: -0.5px;
      line-height: 1.35;
      margin: 0 0 14px;
    }

    h3 {
      font-size: 17px;
      margin: 22px 0 8px;
    }

    p {
      margin: 0 0 14px;
    }

    ul {
      padding-left: 22px;
    }

    li {
      margin-bottom: 9px;
    }

    .note {
      padding: 18px 20px;
      background: var(--background);
      border: 1px solid var(--line);
      border-radius: 12px;
      margin-top: 18px;
    }

    .note p:last-child {
      margin-bottom: 0;
    }

    .contact {
      padding: 24px;
      background: var(--navy);
      color: var(--white);
      border-radius: 14px;
    }

    .contact h2 {
      color: var(--white);
    }

    .contact a {
      color: var(--yellow);
    }

    .contact p:last-child {
      margin-bottom: 0;
    }

    footer {
      padding: 0 24px 36px;
      text-align: center;
      color: var(--muted);
      font-size: 13px;
    }

    footer p {
      margin: 6px 0;
    }

    @media (max-width: 600px) {
      .hero {
        padding: 26px 24px 58px;
      }

      nav ol {
        columns: 1;
      }

      h2 {
        font-size: 21px;
      }

      .intro {
        font-size: 16px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      html {
        scroll-behavior: auto;
      }
    }
  </style>
</head>

<body>
  <a class="skip-link" href="#policy">Skip to privacy policy</a>

  <header class="hero">
    <div class="container">
      <div class="brand" aria-label="PitchUP">
        PITCH<span>UP.</span>
      </div>

      <p class="eyebrow">Your information. Your choices.</p>

      <h1>Privacy policy.</h1>

      <p class="intro">
        This policy explains how PitchUP handles personal information
        when you find, join, and host football games.
      </p>

      <p class="updated">Last updated: REPLACE_PUBLICATION_DATE</p>
    </div>
  </header>

  <main id="policy">
    <article class="card">
      <div class="summary">
        <p>
          PitchUP uses personal information to operate accounts,
          bookings, payments, player profiles, game communication,
          and notifications. This page explains what information is
          involved, who may receive it, and the choices available to you.
        </p>
      </div>

      <nav aria-label="Policy contents">
        <h2>On this page</h2>
        <ol>
          <li><a href="#operator">Who we are</a></li>
          <li><a href="#information">Information we handle</a></li>
          <li><a href="#purposes">How and why we use it</a></li>
          <li><a href="#visibility">What other users can see</a></li>
          <li><a href="#providers">Service providers</a></li>
          <li><a href="#permissions">Permissions and notifications</a></li>
          <li><a href="#retention">Retention and security</a></li>
          <li><a href="#deletion">Account deletion</a></li>
          <li><a href="#rights">Your privacy rights</a></li>
          <li><a href="#transfers">International transfers</a></li>
          <li><a href="#changes">Policy updates</a></li>
          <li><a href="#contact">Contact</a></li>
        </ol>
      </nav>

      <section id="operator">
        <h2>1. Who we are</h2>
        <p>
          PitchUP is operated by REPLACE_OPERATOR_LEGAL_NAME,
          based at REPLACE_BUSINESS_ADDRESS_OR_CONTACT_ADDRESS.
          This operator is responsible for the personal information
          described in this policy.
        </p>
        <p>
          For privacy questions, contact
          <a href="mailto:REPLACE_PRIVACY_EMAIL">REPLACE_PRIVACY_EMAIL</a>.
        </p>
      </section>

      <section id="information">
        <h2>2. Information we handle</h2>
        <p>
          Depending on the features you use, we handle the following
          categories of information:
        </p>

        <ul>
          <li>
            <strong>Account information:</strong>
            your email address, account identifier, authentication
            information, and account settings.
          </li>
          <li>
            <strong>Profile information:</strong>
            details you choose to provide, such as your display name,
            profile photo, playing position, playing level, city,
            biography, and Instagram handle.
          </li>
          <li>
            <strong>Game and booking information:</strong>
            games you join or host, bookings, cancellations,
            invitations, and player awards or nominations.
          </li>
          <li>
            <strong>Communication:</strong>
            game chat messages, support requests, and information
            you send when contacting us.
          </li>
          <li>
            <strong>Payment information:</strong>
            information needed to record payments, refunds,
            promotional eligibility, and transaction status.
            Payment details are handled through Stripe.
          </li>
          <li>
            <strong>Notification information:</strong>
            notification preferences and device push tokens used
            to send notifications to your installation of the app.
          </li>
          <li>
            <strong>Technical information:</strong>
            REPLACE_ACTUAL_LOGGING_AND_DIAGNOSTIC_DATA_DESCRIPTION.
          </li>
        </ul>

        <h3>Location and photo access</h3>
        <p>
          REPLACE_LOCATION_PRACTICES: explain whether location is
          actually accessed, whether precise or approximate location
          is used, whether it leaves the device, and whether it is stored.
        </p>
        <p>
          If you choose to add a profile photo, we process the image
          you select or upload to display it in PitchUP.
        </p>
      </section>

      <section id="purposes">
        <h2>3. How and why we use information</h2>
        <ul>
          <li>To create, authenticate, and manage your account.</li>
          <li>To display games and manage bookings and hosting.</li>
          <li>To process payments, discounts, cancellations, and refunds.</li>
          <li>To provide player profiles, invitations, chat, and awards.</li>
          <li>To send booking updates, reminders, and service messages.</li>
          <li>
            To send optional promotional notifications in accordance
            with your preferences and applicable requirements.
          </li>
          <li>To respond to support requests and investigate problems.</li>
          <li>
            To protect the service against fraud, abuse, and
            unauthorised access, and meet applicable legal obligations.
          </li>
        </ul>

        <h3>Legal bases</h3>
        <p>
          Where applicable data protection law requires a legal basis,
          we rely on performing our agreement with you to provide
          requested services, complying with legal obligations,
          and legitimate interests such as service security and
          support where those interests are not overridden by your rights.
          Where processing requires consent, we ask for it and you
          can withdraw it.
        </p>
        <p>
          REPLACE_OR_CONFIRM_THE_LEGAL_BASES_FOR_YOUR_ACTUAL_PROCESSING.
        </p>
      </section>

      <section id="visibility">
        <h2>4. What other users can see</h2>
        <p>
          PitchUP includes social and game-related features.
          Your player profile and participation may be visible
          to other users according to the feature you use.
        </p>
        <p>
          Messages posted in a game chat are visible to people
          with access to that chat. Information you choose to add
          to your profile may be visible to other signed-in players.
          Avoid putting sensitive information in profiles or messages.
        </p>
        <p>
          REPLACE_OR_CONFIRM_EXACT_PROFILE_ROSTER_AND_HOST_VISIBILITY.
        </p>
      </section>

      <section id="providers">
        <h2>5. Service providers and other disclosures</h2>
        <p>
          We use third-party services to operate PitchUP.
          These providers receive information needed for their role:
        </p>

        <ul>
          <li>
            <strong>Supabase:</strong>
            account authentication, database, and backend services.
          </li>
          <li>
            <strong>Stripe:</strong>
            payment processing and related transaction services.
          </li>
          <li>
            <strong>Expo and platform push services:</strong>
            push notification delivery, including delivery through
            Apple or Google where applicable.
          </li>
          <li>
            <strong>Email services:</strong>
            REPLACE_EMAIL_PROVIDER_AND_WHAT_DATA_IT_RECEIVES.
          </li>
          <li>
            <strong>Maps and other services:</strong>
            REPLACE_MAPS_ANALYTICS_CRASH_REPORTING_AND_OTHER_PROVIDERS_OR_REMOVE.
          </li>
        </ul>

        <p>
          We may also disclose information where required by law,
          to respond to lawful requests, or where necessary to
          protect people, investigate abuse, or establish or defend
          legal claims.
        </p>
      </section>

      <section id="permissions">
        <h2>6. Permissions and notifications</h2>
        <p>
          You can manage notification preferences within PitchUP
          and manage device permissions in your phone's settings.
          Disabling notifications may prevent reminders from
          appearing on your device.
        </p>
        <p>
          Where location, camera, or photo permissions are requested,
          you can manage them through your device settings.
          Features that depend on a permission may be unavailable
          if you decline it.
        </p>
        <p>
          Withdrawing consent does not affect the lawfulness of
          processing that occurred before withdrawal.
        </p>
      </section>

      <section id="retention">
        <h2>7. Retention and security</h2>
        <p>
          We retain information for the time needed for its stated
          purpose, taking account of account activity, service needs,
          dispute handling, and applicable legal requirements.
        </p>
        <p>
          REPLACE_RETENTION_DETAILS: specify the periods or clear
          criteria for account data, messages, support requests,
          transaction records, technical logs, and backups.
        </p>
        <p>
          We use safeguards intended to protect personal information.
          No online service or method of storage can guarantee
          absolute security.
        </p>
      </section>

      <section id="deletion">
        <h2>8. Account deletion</h2>

        <!--
          Publish these instructions only after the in-app
          account deletion flow is implemented and tested.
        -->
        <p>
          To initiate deletion, open PitchUP, go to
          <strong>Account → Delete account</strong>,
          and follow the confirmation steps.
        </p>
        <p>
          REPLACE_DELETION_DETAILS: explain which information is
          deleted or anonymised, the completion timeframe, how
          backups are handled, and any information retained for
          legal obligations or legitimate dispute handling.
        </p>
        <div class="note">
          <p>
            Signing out or uninstalling PitchUP does not by itself
            delete your account.
          </p>
          <p>
            For questions about deletion or retained information,
            contact
            <a href="mailto:REPLACE_PRIVACY_EMAIL">REPLACE_PRIVACY_EMAIL</a>.
          </p>
        </div>
      </section>

      <section id="rights">
        <h2>9. Your privacy rights</h2>
        <p>
          Depending on where you live and the law that applies,
          you may have rights to access, correct, delete, or obtain
          a copy of personal information, restrict processing,
          object to certain processing, or withdraw consent.
          These rights may be subject to legal conditions and exceptions.
        </p>
        <p>
          Contact us to exercise your rights. We may need to verify
          your identity before responding. You may also complain
          to the data protection authority responsible for your region.
        </p>
        <p>
          REPLACE_RELEVANT_SUPERVISORY_AUTHORITY_AND_CONTACT_DETAILS.
        </p>
      </section>

      <section id="transfers">
        <h2>10. International transfers</h2>
        <p>
          REPLACE_INTERNATIONAL_TRANSFER_DETAILS: identify where
          personal information is hosted or processed and explain
          applicable safeguards for transfers outside your jurisdiction.
        </p>
      </section>

      <section id="changes">
        <h2>11. Changes to this policy</h2>
        <p>
          We may update this policy when our practices, features,
          or legal obligations change. We will publish the updated
          policy here and change the date at the top.
          Where required, we will provide additional notice or
          request consent.
        </p>
      </section>

      <section id="contact">
        <div class="contact">
          <h2>12. Contact us</h2>
          <p>
            Privacy enquiries:<br />
            <a href="mailto:REPLACE_PRIVACY_EMAIL">REPLACE_PRIVACY_EMAIL</a>
          </p>
          <p>
            Operator: REPLACE_OPERATOR_LEGAL_NAME<br />
            Address: REPLACE_BUSINESS_ADDRESS_OR_CONTACT_ADDRESS
          </p>
        </div>
      </section>
    </article>
  </main>

  <footer>
    <div class="brand" aria-label="PitchUP">
      PITCH<span style="color: #0964b9;">UP.</span>
    </div>
    <p>Good football. Great company.</p>
    <p>PitchUP · Privacy policy</p>
  </footer>
</body>
</html>
