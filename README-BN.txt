ProMAX Promotion Agency — Website Starter

এই ZIP-এ React + Vite website এবং Supabase client integration-এর প্রাথমিক কাঠামো আছে। এটি এখনো live/deployed নয়।

ফোনে ZIP খোলার পর:
1) কম্পিউটার/ক্লাউড IDE-তে ফোল্ডারটি খুলুন। শুধু Android ফোনে সরাসরি build করা কঠিন হতে পারে।
2) Node.js ইনস্টল করে terminal-এ npm install চালান।
3) .env.example কপি করে .env নাম দিন।
4) VITE_SUPABASE_PUBLISHABLE_KEY-তে Supabase-এর sb_publishable_... key বসান। Secret/service_role key কখনো এখানে বসাবেন না।
5) npm run dev দিয়ে preview, npm run build দিয়ে production build করুন।

Supabase URL ইতিমধ্যে বসানো: https://hoycyumupmdlumywdydi.supabase.co
Admin role app_metadata.role = admin থেকে পড়া হয়। নিরাপত্তার জন্য role client থেকে পরিবর্তন করা যাবে না।

বর্তমান সীমাবদ্ধতা:
- Campaign list Supabase campaigns table থেকে পড়ে।
- Email/password signup/login ও customer order list-এর প্রাথমিক UI আছে।
- Admin page কেবল role যাচাই করে; পূর্ণ admin CRUD এখনো তৈরি হয়নি।
- Payment gateway, USDT/ERC20 on-chain verification, deposit approval, withdrawal processing, support/referral workflow এখনো backend-এ যুক্ত হয়নি।
- Real payment নেওয়ার আগে server-side payment verification, RLS policy review, rate limiting ও deployment configuration আবশ্যক।

CEO: Mostofa Kamal
Admin email: promaxagency2@gmail.com
Wallet currency: USDT (ERC20)
