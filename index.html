<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />
  <meta name="theme-color" content="#0f172a" />
  <meta name="apple-mobile-web-app-capable" content="yes" />
  <meta name="apple-mobile-web-app-status-bar-style" content="default" />
  <meta name="apple-mobile-web-app-title" content="Tour Emails" />
  <title>Tour Email Generator</title>
  <style>
    :root {
      --bg: #f3f6fb;
      --surface: rgba(255,255,255,0.94);
      --text: #0f172a;
      --muted: #5b6473;
      --border: #d9e1ec;
      --accent: #1d4ed8;
      --accent-soft: #dbeafe;
      --shadow: 0 18px 40px rgba(15, 23, 42, 0.08);
      --radius: 22px;
      --success: #15803d;
      --danger: #b91c1c;
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      color: var(--text);
      background:
        radial-gradient(circle at top left, rgba(191,219,254,0.7), transparent 28%),
        radial-gradient(circle at top right, rgba(220,252,231,0.6), transparent 24%),
        var(--bg);
      min-height: 100vh;
    }
    .shell { max-width: 1360px; margin: 0 auto; padding: 18px; padding-bottom: 32px; }
    .hero {
      background: linear-gradient(135deg, rgba(15,23,42,0.96), rgba(30,64,175,0.93));
      color: white; border-radius: 28px; box-shadow: var(--shadow); padding: 20px;
      display: flex; justify-content: space-between; gap: 16px; flex-wrap: wrap; margin-bottom: 18px;
    }
    .hero h1 { margin: 0 0 6px; font-size: 2rem; letter-spacing: -0.02em; }
    .hero p { margin: 0; color: rgba(255,255,255,0.82); max-width: 820px; line-height: 1.45; }
    .hero-actions, .actions, .list-actions { display: flex; gap: 8px; flex-wrap: wrap; }
    .layout { display: grid; grid-template-columns: 430px minmax(0, 1fr); gap: 18px; align-items: start; }
    .card {
      background: var(--surface); backdrop-filter: blur(14px); border: 1px solid rgba(255,255,255,0.6);
      box-shadow: var(--shadow); border-radius: var(--radius); padding: 16px;
    }
    h2 { margin: 0 0 12px; font-size: 1.05rem; letter-spacing: -0.01em; }
    label { display: block; font-size: 0.87rem; font-weight: 700; margin-bottom: 6px; }
    input, select, textarea, button { font: inherit; }
    input, select, textarea {
      width: 100%; border: 1px solid var(--border); border-radius: 14px; padding: 11px 12px;
      background: rgba(255,255,255,0.92); color: var(--text);
    }
    textarea { min-height: 96px; resize: vertical; }
    button { border: 0; border-radius: 14px; padding: 10px 14px; font-weight: 700; cursor: pointer; background: var(--accent); color: white; }
    button.secondary { background: rgba(255,255,255,0.9); color: var(--text); border: 1px solid var(--border); }
    button.ghost { background: var(--accent-soft); color: #1e3a8a; }
    button.success { background: var(--success); }
    button.danger { background: var(--danger); }
    .row, .row-3 { display: grid; gap: 10px; margin-bottom: 10px; }
    .row { grid-template-columns: 1fr 1fr; }
    .row-3 { grid-template-columns: repeat(3,1fr); }
    .stack { margin-bottom: 10px; }
    .tour-grid { display: grid; grid-template-columns: repeat(2, minmax(0,1fr)); gap: 8px; margin-bottom: 10px; }
    .chip {
      display: flex; align-items: center; gap: 8px; padding: 10px; border-radius: 16px;
      border: 1px solid var(--border); background: rgba(255,255,255,0.76); min-height: 52px;
    }
    .tour-block {
      background: rgba(255,255,255,0.8); border: 1px solid var(--border); border-radius: 18px;
      padding: 12px; margin-top: 10px;
    }
    .notice {
      background: #eff6ff; color: #1e3a8a; border: 1px solid #bfdbfe; border-radius: 18px;
      padding: 12px 14px; margin-bottom: 16px; line-height: 1.45; font-size: 0.9rem;
    }
    .template {
      background: #0f172a; color: #e5eefb; border-radius: 18px; padding: 12px; white-space: pre-wrap;
      line-height: 1.45; min-height: 360px; overflow: auto; font-size: 0.9rem;
    }
    .searchbar { margin-bottom: 12px; }
    .list { display: grid; gap: 10px; }
    .item {
      background: rgba(255,255,255,0.85); border: 1px solid var(--border); border-radius: 20px; padding: 14px;
    }
    .item-top {
      display: flex; justify-content: space-between; align-items: start; gap: 10px; flex-wrap: wrap; margin-bottom: 8px;
    }
    .item-grid {
      display: grid; grid-template-columns: repeat(2, minmax(0,1fr)); gap: 8px 14px; font-size: 0.84rem; line-height: 1.45; margin-bottom: 10px;
    }
    .tag {
      display: inline-flex; align-items: center; gap: 6px; padding: 7px 10px; border-radius: 999px;
      background: rgba(255,255,255,0.85); border: 1px solid var(--border); font-size: 0.78rem; font-weight: 700;
    }
    .subtle { color: var(--muted); font-size: 0.84rem; line-height: 1.45; }
    .small { font-size: 0.82rem; }
    .empty { color: var(--muted); padding: 12px 0; }
    .footer-note { margin-top: 10px; color: var(--muted); font-size: 0.82rem; line-height: 1.45; }
    @media (max-width: 1050px) { .layout { grid-template-columns: 1fr; } }
    @media (max-width: 700px) {
      .shell { padding: 12px; }
      .hero { padding: 16px; border-radius: 24px; }
      .hero h1 { font-size: 1.6rem; }
      .row, .row-3, .tour-grid, .item-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <div class="shell">
    <div class="hero">
      <div>
        <h1>Tour Email Generator</h1>
        <p>Single-file app focused on one job: save a constituent group, assign statuses to up to 6 tours, and generate confirmation, unavailable, follow-up, arrival, and departure emails using your office language.</p>
      </div>
      <div class="hero-actions">
        <button class="secondary" id="exportBtn">Export</button>
        <button class="secondary" id="importBtn">Import</button>
        <button class="success" id="installBtn" style="display:none;">Install app</button>
        <input type="file" id="importFile" accept="application/json" hidden />
      </div>
    </div>

    <div class="notice">
      Calendar and reminder features have been removed. This version prioritizes fast email generation from saved groups and tour status language.
    </div>

    <div class="layout">
      <div>
        <div class="card">
          <h2>Create group</h2>

          <div class="stack">
            <label for="groupName">Group / constituent name</label>
            <input id="groupName" placeholder="Smith Family or West Scranton HS" />
          </div>

          <div class="row">
            <div>
              <label for="contactName">Contact name</label>
              <input id="contactName" placeholder="Primary contact" />
            </div>
            <div>
              <label for="contactEmail">Contact email</label>
              <input id="contactEmail" type="email" placeholder="name@example.com" />
            </div>
          </div>

          <div class="row">
            <div>
              <label for="partySize">Party size</label>
              <input id="partySize" type="number" min="1" placeholder="10" />
            </div>
            <div>
              <label for="staffName">Your name</label>
              <input id="staffName" placeholder="Tour coordinator / staffer" />
            </div>
          </div>

          <div class="row">
            <div>
              <label for="coordinatorName">Coordinator sign-off</label>
              <input id="coordinatorName" placeholder="Tour coordinator name" />
            </div>
            <div>
              <label for="officeLine">Office phone</label>
              <input id="officeLine" value="(202) 225-4540" />
            </div>
          </div>

          <div class="stack">
            <label for="groupNotes">General notes</label>
            <textarea id="groupNotes" placeholder="Anything internal or worth remembering for this group"></textarea>
          </div>

          <label>Select up to 6 tours</label>
          <div class="tour-grid" id="tourSelector"></div>
          <div id="tourBlocks"></div>

          <div class="actions">
            <button id="saveBtn">Save group</button>
          </div>

          <div class="footer-note">
            Each selected tour gets its own date, time, and status language block. The email generator combines those blocks into one group email.
          </div>
        </div>
      </div>

      <div>
        <div class="card">
          <h2>Email generation</h2>
          <div class="row">
            <div>
              <label for="emailMode">Email type</label>
              <select id="emailMode">
                <option value="introduction">Introduction</option>
                <option value="unavailable">Unavailable</option>
                <option value="followup">Follow up</option>
                <option value="arrival">Arrival reminder</option>
                <option value="departure">Departure</option>
              </select>
            </div>
            <div>
              <label for="selectedGroup">Selected group</label>
              <select id="selectedGroup"></select>
            </div>
          </div>

          <div class="actions" style="margin-bottom: 12px;">
            <button id="generateBtn">Generate email</button>
            <button class="secondary" id="copyBtn">Copy email</button>
          </div>

          <div class="template" id="emailOutput">Save a group, select it, and generate an email.</div>
        </div>

        <div class="card" style="margin-top:18px;">
          <div class="item-top" style="margin-bottom:12px;">
            <div>
              <h2 style="margin:0 0 4px;">Saved groups</h2>
              <div class="small subtle" id="groupCount"></div>
            </div>
          </div>

          <div class="searchbar">
            <input id="searchInput" placeholder="Search by group, contact, email, or tour type" />
          </div>

          <div class="list" id="groupList"></div>
        </div>
      </div>
    </div>
  </div>

  <script>
    const TOUR_OPTIONS = [
      'Capitol Tour',
      'Library of Congress Tour',
      'White House Tour',
      'SCOTUS Tour',
      'FBI Tour',
      'BEP Tour'
    ];

    const TOUR_STATUS_OPTIONS = {
      'White House Tour': [
        'Please RSVP',
        'Confirmation',
        'Pending',
        'No Availability',
        'Member Pass',
        'Cancelled Reservation'
      ],
      'Capitol Tour': [
        'Confirmation',
        'Staff-Led Confirmation',
        'No Availability'
      ],
      'Library of Congress Tour': [
        'Confirmation',
        'Pending',
        'No Availability'
      ],
      'SCOTUS Tour': [
        'Confirmation',
        'No Availability',
        'No Reserved Seating',
        'Pending',
        'Group Larger Than 6'
      ],
      'BEP Tour': [
        'Requested',
        'Confirmation',
        'Group of 10 or More',
        'Pending',
        'No Availability'
      ],
      'FBI Tour': [
        'Need Information',
        'Tour Submitted',
        'No Availability'
      ]
    };

    const STATUS_TEMPLATES = {
      'White House Tour': {
        'Please RSVP': group => `White House - I have submitted a White House tour request for ${formatDay(group)} at ${formatTime(group)} on your behalf. You should have received an email from the White House prompting you to submit information for each person in your group to White House security. This information must exactly match information on your government-issued ID and must be submitted within three days after you receive the email. You will receive confirmation or denial of your tour 14-21 days before the requested date. If you do not RSVP by the deadline, [DATE AND TIME IN PT IN WHITE HOUSE WEBSITE] you will not be able to get the tour. Your reservation link is below:\nINSERT RESERVATION LINK\nPlease also note that the White House requires all guests over the age of 15 to present a REAL ID or valid passport when they arrive for their tour.`,
        'Confirmation': group => `White House - The White House has scheduled your group for ${formatDay(group)} at ${formatTime(group)}. You should have already received a confirmation email with your pass directly from the White House.\nDay-of instructions: All visitors over the age of 18 and all non-US citizens regardless of age must bring a REAL ID or valid passport. Please check your receipt for further instructions.`,
        'Pending': () => `White House – We have received your request and will reserve your tour as soon as the White House opens up the dates you’ve requested for reservations.`,
        'No Availability': () => `White House – Unfortunately, the White House has no available tour spots during the dates you provided. Please let us know if there are any other tour requests we can submit for you!`,
        'Member Pass': group => `White House – We are happy to let you know that we’re using one of our limited member passes for your visit. Pending the submission of your RSVPs, the White House has scheduled your group for ${formatDay(group)} at 8:00 AM.\nDay-of instructions:\nAll confirmed groups must have a “Member Pass” at hand that will be distributed from this office. Groups without this pass will be turned away.\nPlease arrange to pick up the Member Pass with the tour coordinator before your tour begins or stop by our office at 209 Cannon Office Building between the hours of 10am to 4pm prior to the tour date.\nPlease also note that the White House requires all guests over the age of 15 to present a REAL ID or valid passport when they arrive for their tour.`,
        'Cancelled Reservation': () => `White House - Unfortunately, the White House did not receive an RSVP from each individual prior to the deadline, which has led to the cancellation of your tour request. Please let us know if you would like us to resubmit for a White House tour [PLEASE CHECK THAT THEY ARE STILL AVAILABLE BEFORE OFFERING TO RESUBMIT] or if there are any additional tour requests we can submit for you!`
      },
      'Capitol Tour': {
        'Confirmation': group => `U.S. Capitol Building - You should have already received a confirmation email directly from the Capitol Visitor Center for a tour on ${formatDay(group)} at ${formatTime(group)}. Your receipt is attached here.\nDay-of instructions: Enter for your tour in the Capitol Visitors Center, found beneath the east plaza of the Capitol. Make sure to have the confirmation number on your email receipt handy, and allow at least 30 minutes for going through security. Outside food and beverages (including water) are not allowed inside the Capitol Visitors Center.`,
        'Staff-Led Confirmation': group => `U.S. Capitol Building - I am happy to say that we have scheduled a staff-led tour for you and your group on ${formatDay(group)} at ${formatTime(group)}.\nDay-of instructions: Please meet your tour guide(s) at Cannon 209, Congressman Josh Harder’s office. Allow at least 30 minutes for going through security. Please note that outside food and beverages (including water) are not allowed inside the Capitol Visitors Center. Feel free to drop off any food or beverages you would not like to discard in Cannon 209.`,
        'No Availability': () => `U.S. Capitol Building - The Capitol Visitor Center was fully booked for advanced passes during your visit. There are a limited number of same day walk-up tickets, and we strongly advise that you arrive early and be prepared to wait if you would like to pursue that option. Please let us know if there are any other tour requests we can submit for you!`
      },
      'Library of Congress Tour': {
        'Confirmation': group => `Library of Congress - You should have already received a confirmation email directly from the Library of Congress for a timed entry pass on ${formatDay(group)} at ${formatTime(group)}.\nDay-of instructions: Make sure to have the confirmation number on your email receipt handy, and allow at least 15 minutes for going through security.`,
        'Pending': () => `Library of Congress – We have received your request and will reserve your timed entry pass as soon as the Library opens up the dates you’ve requested for reservations.`,
        'No Availability': () => `Library of Congress - Unfortunately there are no more reserved spaces available during the days and times you requested. Walk-in timed entry passes of the Library of Congress are available on a first-come, first-served basis without prior reservations; you can find more information about walk-ins on their website.`
      },
      'SCOTUS Tour': {
        'Confirmation': group => `Supreme Court Lecture - I am happy to say that we have scheduled reserved seating for your group on ${formatDay(group)} at 12:30 pm. The reservation will be under your name.\nDay-of instructions: A line forms in the Great Hall on the first floor before each lecture. It is advisable to join the line at least 15 minutes prior to the lecture’s start time. Please be on time for the lectures, as the Supreme Court does not accommodate late entries.`,
        'No Availability': () => `Supreme Court Lecture - Unfortunately the Supreme Court had no availability for reserved lecture seating for the dates you provided. Please visit the Supreme Court website to see their calendar and anticipated tour slots for non-reserved seating on a first-come, first-served basis.\nDay-of instructions: A line forms in the Great Hall on the first floor before each lecture. It is advisable to join the line at least 30 minutes prior to the lecture’s start time. Please be on time for the lectures, as the Supreme Court does not accommodate late entries.`,
        'No Reserved Seating': () => `Supreme Court Lecture - Unfortunately the Supreme Court is not offering reserved seating available on the days you will be in Washington. However, they may still be holding lectures on a walk-in basis only. Please visit the Supreme Court website to see their calendar and anticipated tour slots.`,
        'Pending': () => `Supreme Court Lecture – We have received your request and will reserve your tour as soon as the Supreme Court opens up the dates you’ve requested for reservations.`,
        'Group Larger Than 6': () => `Supreme Court Lecture - Unfortunately the Supreme Court does not allow reserved seating for groups of more than 6. They do allow large groups to walk-in to attend lectures, please visit the Supreme Court website to see their calendar and anticipated tour slots for non-reserved seating on a first-come, first-served basis.`
      },
      'BEP Tour': {
        'Requested': () => `Bureau of Engraving and Printing (BEP) – We have submitted your tour request to the BEP! We’ll update you as soon as we hear back from the BEP.`,
        'Confirmation': group => `Bureau of Engraving and Printing (BEP) - The BEP has scheduled your group for ${formatDay(group)} at ${formatTime(group)}.\nDay-of instructions: Make sure to have the confirmation number on your email receipt handy, and make sure to arrive early - the BEP does not accommodate groups that are more than 10 minutes late. The Tour and Visitor Center is near the National Mall, just south of Independence Avenue, SW, between 14th Street and Raoul Wallenberg Place (15th Street) in Washington, D.C. Visitors enter through the Tour and Visitor Center entrance on 14th Street.`,
        'Group of 10 or More': () => `Bureau of Engraving and Printing - The Bureau of Engraving and Printings does not allow congressional staff to book tours for constituent groups of 10 or more, but it does allow constituents to do so themselves. Please see the attached form, complete it, and email the completed form to tourscheduler@bep.gov. Please note that the BEP also allows walk-in tours Monday through Friday. You can find more information on their website.`,
        'Pending': () => `Bureau of Engraving and Printing – We have received your request and will reserve your tour as soon as the Bureau of Engraving and Printing opens the dates you’ve requested for reservations.`,
        'No Availability': () => `Bureau of Engraving and Printing (BEP) – Unfortunately, the Bureau of Engraving and Printing has no spaces available for your requested dates and times. The BEP allows walk-in tours Monday through Friday. You can find more information on their website.`
      },
      'FBI Tour': {
        'Need Information': () => `FBI – Due to FBI security, we are unable to request a tour if we do not have the information listed below for each member of your party. As of [TODAY’S DATE], the FBI has the dates you’ve requested open for reservations, but FBI tours are very limited and fill up quickly.\nTo ensure that we are able to submit your request, please collect the following information from each member of your group.\nFirst Name\nMiddle Name\nLast Name\nSuffix (If Applicable)\nBirthdate\nSocial Security Number (not required for guests under 16 years of age)\nCountry of Birth\nCitizenship\nGreen Card Number (If Applicable)\nPassport or Visa (If Applicable)\nOnce you have collected this information from all members of your party, call our main office line at (202)225-4540 and ask to book an FBI tour.`,
        'Tour Submitted': group => `FBI – Your tour for the FBI has been requested for ${formatDay(group)} at ${formatTime(group)}. You will receive email from the FBI stating whether your group has been approved for the tour at least three weeks prior to your scheduled visit.`,
        'No Availability': () => `FBI - Unfortunately the FBI has no more available tour spots during your trip to DC. If there’s anything else we can do to make your trip to Washington great, please let us know!`
      }
    };

    const STORAGE_KEY = 'tourEmailGeneratorV1';
    let deferredPrompt = null;

    const state = {
      groups: loadGroups(),
      selectedTours: [],
      search: '',
      currentGroupId: ''
    };

    const els = {
      groupName: document.getElementById('groupName'),
      contactName: document.getElementById('contactName'),
      contactEmail: document.getElementById('contactEmail'),
      partySize: document.getElementById('partySize'),
      staffName: document.getElementById('staffName'),
      coordinatorName: document.getElementById('coordinatorName'),
      officeLine: document.getElementById('officeLine'),
      groupNotes: document.getElementById('groupNotes'),
      tourSelector: document.getElementById('tourSelector'),
      tourBlocks: document.getElementById('tourBlocks'),
      saveBtn: document.getElementById('saveBtn'),
      emailMode: document.getElementById('emailMode'),
      selectedGroup: document.getElementById('selectedGroup'),
      generateBtn: document.getElementById('generateBtn'),
      copyBtn: document.getElementById('copyBtn'),
      emailOutput: document.getElementById('emailOutput'),
      groupCount: document.getElementById('groupCount'),
      groupList: document.getElementById('groupList'),
      searchInput: document.getElementById('searchInput'),
      exportBtn: document.getElementById('exportBtn'),
      importBtn: document.getElementById('importBtn'),
      importFile: document.getElementById('importFile'),
      installBtn: document.getElementById('installBtn')
    };

    init();

    function init() {
      renderSelector();
      renderTourBlocks();
      renderGroupPicker();
      renderList();
      wire();
      setupPWA();
      if (state.groups.length) {
        state.currentGroupId = state.groups[0].id;
        els.selectedGroup.value = state.currentGroupId;
        generateEmail();
      }
    }

    function wire() {
      els.saveBtn.addEventListener('click', saveGroup);
      els.generateBtn.addEventListener('click', generateEmail);
      els.copyBtn.addEventListener('click', () => copyText(els.emailOutput.textContent));
      els.emailMode.addEventListener('change', generateEmail);
      els.selectedGroup.addEventListener('change', e => { state.currentGroupId = e.target.value; generateEmail(); });
      els.searchInput.addEventListener('input', e => { state.search = e.target.value.toLowerCase().trim(); renderList(); });
      els.exportBtn.addEventListener('click', exportData);
      els.importBtn.addEventListener('click', () => els.importFile.click());
      els.importFile.addEventListener('change', importData);
      els.installBtn.addEventListener('click', installApp);
    }

    function setupPWA() {
      if ('serviceWorker' in navigator) registerServiceWorker();
      injectManifest();
      window.addEventListener('beforeinstallprompt', e => {
        e.preventDefault();
        deferredPrompt = e;
        els.installBtn.style.display = 'inline-flex';
      });
    }

    async function installApp() {
      if (!deferredPrompt) return;
      deferredPrompt.prompt();
      await deferredPrompt.userChoice;
      deferredPrompt = null;
      els.installBtn.style.display = 'none';
    }

    function injectManifest() {
      const manifest = {
        name: 'Tour Email Generator',
        short_name: 'Tour Emails',
        start_url: './',
        display: 'standalone',
        background_color: '#f3f6fb',
        theme_color: '#0f172a',
        icons: [
          { src: generateIcon(), sizes: '192x192', type: 'image/svg+xml', purpose: 'any' },
          { src: generateIcon(), sizes: '512x512', type: 'image/svg+xml', purpose: 'any' }
        ]
      };
      const blob = new Blob([JSON.stringify(manifest)], { type: 'application/manifest+json' });
      const url = URL.createObjectURL(blob);
      const link = document.createElement('link');
      link.rel = 'manifest';
      link.href = url;
      document.head.appendChild(link);
    }

    function generateIcon() {
      const svg = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><rect width="512" height="512" rx="110" fill="#0f172a"/><rect x="78" y="92" width="356" height="328" rx="38" fill="#ffffff"/><rect x="110" y="170" width="292" height="36" rx="18" fill="#dbeafe"/><rect x="110" y="234" width="292" height="36" rx="18" fill="#dcfce7"/><rect x="110" y="298" width="292" height="36" rx="18" fill="#fef3c7"/></svg>`;
      return 'data:image/svg+xml;charset=utf-8,' + encodeURIComponent(svg);
    }

    async function registerServiceWorker() {
      const sw = `
        const CACHE = 'tour-email-generator-v1';
        self.addEventListener('install', event => {
          event.waitUntil(caches.open(CACHE).then(cache => cache.addAll(['./'])));
          self.skipWaiting();
        });
        self.addEventListener('activate', event => {
          event.waitUntil(self.clients.claim());
        });
        self.addEventListener('fetch', event => {
          if (event.request.method !== 'GET') return;
          event.respondWith(caches.match(event.request).then(cached => cached || fetch(event.request).then(response => {
            const copy = response.clone();
            caches.open(CACHE).then(cache => cache.put(event.request, copy));
            return response;
          }).catch(() => caches.match('./'))));
        });
      `;
      const blob = new Blob([sw], { type: 'application/javascript' });
      const swUrl = URL.createObjectURL(blob);
      try { await navigator.serviceWorker.register(swUrl); } catch (e) {}
    }

    function renderSelector() {
      els.tourSelector.innerHTML = '';
      TOUR_OPTIONS.forEach(tour => {
        const label = document.createElement('label');
        label.className = 'chip';
        label.innerHTML = `<input type="checkbox" value="${tour}" ${state.selectedTours.includes(tour) ? 'checked' : ''}> <span>${tour}</span>`;
        label.querySelector('input').addEventListener('change', e => {
          if (e.target.checked) {
            if (state.selectedTours.length >= 6) {
              e.target.checked = false;
              alert('You can select up to 6 tours at one time.');
              return;
            }
            state.selectedTours.push(tour);
          } else {
            state.selectedTours = state.selectedTours.filter(t => t !== tour);
          }
          renderTourBlocks();
        });
        els.tourSelector.appendChild(label);
      });
    }

    function renderTourBlocks() {
      els.tourBlocks.innerHTML = '';
      if (!state.selectedTours.length) {
        els.tourBlocks.innerHTML = '<div class="empty">Select one or more tours to enter booked dates, times, and status language.</div>';
        return;
      }

      state.selectedTours.forEach((tour, i) => {
        const options = TOUR_STATUS_OPTIONS[tour].map(s => `<option value="${s}">${s}</option>`).join('');
        const div = document.createElement('div');
        div.className = 'tour-block';
        div.innerHTML = `
          <div class="item-top" style="margin-bottom:10px;">
            <strong>${tour}</strong>
            <span class="tag">Tour ${i + 1}</span>
          </div>
          <div class="row-3">
            <div>
              <label>Date</label>
              <input type="date" data-tour="${tour}" data-field="date" />
            </div>
            <div>
              <label>Time</label>
              <input type="time" data-tour="${tour}" data-field="time" value="10:00" />
            </div>
            <div>
              <label>Status</label>
              <select data-tour="${tour}" data-field="status">${options}</select>
            </div>
          </div>
          <div>
            <label>Optional notes / replacement text</label>
            <textarea data-tour="${tour}" data-field="notes" placeholder="Use if you want to remember a reservation link, special instructions, or internal notes."></textarea>
          </div>
        `;
        els.tourBlocks.appendChild(div);
      });
    }

    function saveGroup() {
      const groupName = els.groupName.value.trim();
      if (!groupName) return alert('Enter a group or constituent name.');
      if (!state.selectedTours.length) return alert('Select at least one tour.');

      const group = {
        id: crypto.randomUUID(),
        groupName,
        contactName: els.contactName.value.trim(),
        contactEmail: els.contactEmail.value.trim(),
        partySize: els.partySize.value.trim(),
        staffName: els.staffName.value.trim(),
        coordinatorName: els.coordinatorName.value.trim(),
        officeLine: els.officeLine.value.trim() || '(202) 225-4540',
        groupNotes: els.groupNotes.value.trim(),
        createdAt: new Date().toISOString(),
        tours: state.selectedTours.map(tour => ({
          id: crypto.randomUUID(),
          tourType: tour,
          date: getFieldValue(tour, 'date'),
          time: getFieldValue(tour, 'time'),
          status: getFieldValue(tour, 'status') || TOUR_STATUS_OPTIONS[tour][0],
          notes: getFieldValue(tour, 'notes')
        }))
      };

      state.groups = [group, ...state.groups].sort((a, b) => a.groupName.localeCompare(b.groupName));
      state.currentGroupId = group.id;
      persist();
      clearForm();
      renderGroupPicker();
      renderList();
      generateEmail();
      alert(`Saved ${group.groupName} with ${group.tours.length} tour${group.tours.length === 1 ? '' : 's'}.`);
    }

    function clearForm() {
      els.groupName.value = '';
      els.contactName.value = '';
      els.contactEmail.value = '';
      els.partySize.value = '';
      els.staffName.value = '';
      els.coordinatorName.value = '';
      els.officeLine.value = '(202) 225-4540';
      els.groupNotes.value = '';
      state.selectedTours = [];
      renderSelector();
      renderTourBlocks();
    }

    function renderGroupPicker() {
      els.selectedGroup.innerHTML = '';
      if (!state.groups.length) {
        els.selectedGroup.innerHTML = '<option value="">No saved groups</option>';
        return;
      }
      state.groups.forEach(group => {
        const opt = document.createElement('option');
        opt.value = group.id;
        opt.textContent = group.groupName;
        els.selectedGroup.appendChild(opt);
      });
      if (!state.currentGroupId || !state.groups.some(g => g.id === state.currentGroupId)) {
        state.currentGroupId = state.groups[0].id;
      }
      els.selectedGroup.value = state.currentGroupId;
    }

    function renderList() {
      const filtered = state.groups.filter(matchesSearch);
      els.groupCount.textContent = `${filtered.length} shown · ${state.groups.length} total groups`;
      els.groupList.innerHTML = '';
      if (!filtered.length) {
        els.groupList.innerHTML = '<div class="empty">No groups match your search.</div>';
        return;
      }

      filtered.forEach(group => {
        const item = document.createElement('div');
        item.className = 'item';
        item.innerHTML = `
          <div class="item-top">
            <div>
              <strong>${group.groupName}</strong>
              <div class="small subtle">${group.tours.map(t => `${t.tourType} (${t.status})`).join(' · ')}</div>
            </div>
            <span class="tag">${group.tours.length} tours</span>
          </div>
          <div class="item-grid">
            <div><strong>Contact:</strong> ${group.contactName || '—'}</div>
            <div><strong>Email:</strong> ${group.contactEmail || '—'}</div>
            <div><strong>Party size:</strong> ${group.partySize || '—'}</div>
            <div><strong>Staff:</strong> ${group.staffName || group.coordinatorName || '—'}</div>
          </div>
          <div style="margin-bottom:10px;">
            ${group.tours.map(t => `<div class="tag" style="margin:4px 6px 0 0; display:inline-flex;">${t.tourType} · ${t.status}${t.date ? ' · ' + t.date : ''}${t.time ? ' ' + t.time : ''}</div>`).join('')}
          </div>
          <div class="list-actions">
            <button class="ghost" data-action="select" data-id="${group.id}">Use for email</button>
            <button class="secondary" data-action="copy" data-id="${group.id}">Copy current email</button>
            <button class="danger" data-action="delete" data-id="${group.id}">Delete</button>
          </div>
        `;

        item.querySelector('[data-action="select"]').addEventListener('click', () => {
          state.currentGroupId = group.id;
          renderGroupPicker();
          generateEmail();
        });
        item.querySelector('[data-action="copy"]').addEventListener('click', () => {
          state.currentGroupId = group.id;
          renderGroupPicker();
          generateEmail();
          copyText(els.emailOutput.textContent);
        });
        item.querySelector('[data-action="delete"]').addEventListener('click', () => {
          if (confirm(`Delete ${group.groupName}?`)) {
            state.groups = state.groups.filter(g => g.id !== group.id);
            persist();
            renderGroupPicker();
            renderList();
            generateEmail();
          }
        });
        els.groupList.appendChild(item);
      });
    }

    function generateEmail() {
      const group = state.groups.find(g => g.id === state.currentGroupId);
      if (!group) {
        els.emailOutput.textContent = 'Save a group, select it, and generate an email.';
        return;
      }
      els.emailOutput.textContent = buildEmail(els.emailMode.value, group);
    }

    function buildEmail(mode, group) {
      const statusBlock = group.tours.map(tour => buildTourStatusText(group, tour)).join('\n\n');
      const contact = group.contactName || '___';
      const staff = group.staffName || '[Insert your name]';
      const coordinator = group.coordinatorName || '[Tour coordinator name]';
      const phone = group.officeLine || '(202) 225-4540';

      if (mode === 'departure') {
        return `Dear ${contact},\n\nOn behalf of myself and Congressman Josh Harder, we want to thank you very much for letting us be a part of your DC experience. We hope you enjoyed your time here and that you think of us next time you come by!\n\nIf you have any questions or suggestions, please feel free to call our DC main office line ${phone} and ask for the Tour Coordinator.`;
      }

      if (mode === 'arrival') {
        return `Dear ${contact},\n\nThis is a reminder that your scheduled tour(s) are coming up soon. We are extremely excited to welcome you into our nation’s capital!\nHere is the current status of your tours:\n${statusBlock}\n\nIf you have any questions, concerns, or a change of plans, feel free to email us back at this email or call our DC main office line at ${phone} and ask for ${staff}.\n\nBest,\n${coordinator}`;
      }

      if (mode === 'followup') {
        return `Dear ${contact},\n\nThank you for applying for tours through our DC office – we’re excited to welcome you here! Please continue to keep an eye out for emails from us to stay up to date on the status of your tour request!\nHere is an update on the current status of your tours:\n${statusBlock}\n\nIf you have any questions, concerns, or a change of plans, feel free to email us back at this email or call our DC main office line at ${phone} and ask for ${staff}.\n\nBest,\n${coordinator}`;
      }

      if (mode === 'unavailable') {
        return `Dear ${contact},\n\nThank you for applying for tours through our DC office. Here is an update on the current status of your tours:\n${statusBlock}\n\nWe recognize that tours in DC fill up very quickly, and we apologize that none of your requested tours were available. Please let us know if there are any other tours that you are interested in during your visit, and if you have any questions, concerns, or a change of plans, feel free to email us back at this email or call our DC main office line at ${phone} and ask for ${staff}.\n\nBest,\n${coordinator}`;
      }

      return `SUBJECT: Office of Rep. Harder – DC Tours\n\nDear ${contact},\n\nThank you for applying for tours through our DC office – we’re excited to welcome you here! Each tour has a different application process on our end, and we’ll update you as we hear back. Keep an eye out for emails from us to stay up to date.\nHere is the current status of your tours:\n${statusBlock}\n\nIf you have any questions, concerns, or a change of plans, feel free to email us back at this email or call our DC main office line at ${phone} and ask for ${staff}.\n\nBest,\n${coordinator}`;
    }

    function buildTourStatusText(group, tour) {
      const fn = STATUS_TEMPLATES[tour.tourType]?.[tour.status];
      if (!fn) return `${tour.tourType} - [No template found for ${tour.status}]`;
      return fn({ ...tour, groupName: group.groupName, contactName: group.contactName, partySize: group.partySize });
    }

    function formatDay(tour) {
      if (!tour.date) return 'DAY';
      const [y, m, d] = tour.date.split('-').map(Number);
      const date = new Date(y, m - 1, d);
      return date.toLocaleDateString(undefined, { weekday: 'long', month: 'long', day: 'numeric' });
    }

    function formatTime(tour) {
      if (!tour.time) return 'TIME';
      const [hours, minutes] = tour.time.split(':').map(Number);
      const date = new Date();
      date.setHours(hours, minutes, 0, 0);
      return date.toLocaleTimeString([], { hour: 'numeric', minute: '2-digit' });
    }

    function matchesSearch(group) {
      if (!state.search) return true;
      const text = [
        group.groupName,
        group.contactName,
        group.contactEmail,
        group.groupNotes,
        ...(group.tours || []).flatMap(t => [t.tourType, t.status, t.date, t.time, t.notes])
      ].join(' ').toLowerCase();
      return text.includes(state.search);
    }

    function getFieldValue(tour, field) {
      return document.querySelector(`[data-tour="${cssEscape(tour)}"][data-field="${field}"]`)?.value || '';
    }

    function exportData() {
      const blob = new Blob([JSON.stringify(state.groups, null, 2)], { type: 'application/json' });
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = 'tour-email-groups.json';
      a.click();
      URL.revokeObjectURL(url);
    }

    function importData(e) {
      const file = e.target.files?.[0];
      if (!file) return;
      const reader = new FileReader();
      reader.onload = () => {
        try {
          const parsed = JSON.parse(reader.result);
          if (!Array.isArray(parsed)) throw new Error('Invalid file');
          state.groups = parsed;
          state.currentGroupId = state.groups[0]?.id || '';
          persist();
          renderGroupPicker();
          renderList();
          generateEmail();
          alert('Data imported.');
        } catch {
          alert('Import failed. Use a valid export file from this app.');
        }
      };
      reader.readAsText(file);
      e.target.value = '';
    }

    function persist() {
      localStorage.setItem(STORAGE_KEY, JSON.stringify(state.groups));
    }

    function loadGroups() {
      try {
        const raw = localStorage.getItem(STORAGE_KEY);
        return raw ? JSON.parse(raw) : [];
      } catch {
        return [];
      }
    }

    function cssEscape(value) {
      return window.CSS && CSS.escape ? CSS.escape(value) : value.replace(/"/g, '\\"');
    }

    async function copyText(text) {
      try {
        await navigator.clipboard.writeText(text);
        alert('Copied to clipboard.');
      } catch {
        alert('Clipboard copy failed on this device/browser.');
      }
    }
  </script>
</body>
</html>
