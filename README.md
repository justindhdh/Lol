<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bet With Justin</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900 font-sans">
  <div class="max-w-xl mx-auto p-6 mt-10 bg-white rounded-2xl shadow-xl">
    <h1 class="text-3xl font-bold text-center mb-6">📲 Place Your Football Bet</h1>

    <div class="text-center mb-6">
      <p class="text-lg">Step 1: Send Your Bet Money</p>
      <a href="https://cash.app/$YourCashTag" target="_blank" class="block mt-2 text-2xl text-green-600 font-bold">
        $YourCashTag
      </a>
      <p class="text-sm text-gray-600 mt-1">Tap above to open Cash App</p>
    </div>

    <hr class="my-6" />

    <p class="text-center text-lg mb-4">Step 2: Submit Your Bet Details</p>

    <form action="https://formsubmit.co/reidjustin150@gmail.com" method="POST" class="space-y-4">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_next" value="https://thankyou-page.com">

      <div>
        <label class="block text-sm font-medium">Your Name</label>
        <input type="text" name="name" class="w-full mt-1 p-2 border rounded-md" placeholder="John Doe" required />
      </div>

      <div>
        <label class="block text-sm font-medium">Football Match</label>
        <input type="text" name="match" class="w-full mt-1 p-2 border rounded-md" placeholder="Man City vs Real Madrid" required />
      </div>

      <div>
        <label class="block text-sm font-medium">Bet Type</label>
        <input type="text" name="bet_type" class="w-full mt-1 p-2 border rounded-md" placeholder="Team to win, Scoreline, etc." required />
      </div>

      <div>
        <label class="block text-sm font-medium">Bet Amount ($)</label>
        <input type="number" name="amount" class="w-full mt-1 p-2 border rounded-md" placeholder="25" required />
      </div>

      <div>
        <label class="block text-sm font-medium">Odds (optional)</label>
        <input type="text" name="odds" class="w-full mt-1 p-2 border rounded-md" placeholder="2.75" />
      </div>

      <div>
        <label class="block text-sm font-medium">Contact Info</label>
        <input type="text" name="contact" class="w-full mt-1 p-2 border rounded-md" placeholder="Email or phone" />
      </div>

      <button type="submit" class="w-full bg-green-600 hover:bg-green-700 text-white py-2 rounded-lg font-semibold">
        Submit Bet Info
      </button>
    </form>

    <p class="text-xs text-gray-500 mt-6 text-center">
      By submitting, you agree that all bets are placed at your own risk. No guaranteed returns or refunds. You must be 18+.
    </p>
  </div>
</body>
</html>
