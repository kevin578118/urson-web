@supabase/supabase-js 2.105.1 (Supabase, MIT), build UMD — https://github.com/supabase/supabase-js
Servi depuis ce site, jamais depuis un CDN : la page Confidentialité promet zéro appel tiers.
Fichier copié tel quel depuis dist/umd/supabase.js du paquet npm — ne pas éditer à la main.
Ne sert qu'à la page /pro/ (espace organisateur) : signInWithOtp / verifyOtp et les appels
authentifiés à l'Edge Function organizer-account. Expose window.supabase.createClient.
Mettre à jour : copier à nouveau dist/umd/supabase.js depuis
app-activites-enfants/node_modules/@supabase/supabase-js après un bump de version.
