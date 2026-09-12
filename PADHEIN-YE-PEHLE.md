# QuickBites Website — Aagay Kya Karna Hai

Aap ki website ban gayi hai. 5 pages hain: Home, Recipes, ek sample recipe post, About, Contact.

## Step 1: Website ko Live Karna (Hosting)

Free option (beginners k liye best):
1. **GitHub Pages** — free, reliable. GitHub par account banayen, ek "repository" banayen, ye saari files usmein upload karen, phir Settings > Pages se "GitHub Pages" on karen. Kuch minutes mein aap ki site live ho jayegi (aap ko ek link mil jayega jaisay `username.github.io/sitename`).
2. **Netlify / Vercel** — ye bhi free hain aur GitHub Pages se thora asaan hain — bas is folder ko drag-and-drop karen unki website par.

Paid option (professional look k liye, zaroori nahi shuru mein):
- Hostinger ya Namecheap se domain (jaise `quickbites.com`) aur hosting khareed sakte hain — $2-5/month se shuru hoti hai.

## Step 2: Content Barhayen

Abhi sirf 1 poora recipe post hai (`recipe-garlic-butter-pasta.html`) — baqi cards `recipes.html` par sirf preview hain, unke poore pages nahi bane.

Har naye recipe k liye:
1. `recipe-garlic-butter-pasta.html` ko copy karen, naya naam den (jaise `recipe-chicken-karahi.html`)
2. Us file k andar title, ingredients, aur steps apne naye recipe se replace karen
3. `recipes.html` mein us recipe k card ko naye page se link karen

**AdSense approval k liye kam se kam 15-20 achi, original recipe posts honi chahiye** — jitni zyada quality content utna behtar chance.

## Step 3: Google AdSense Apply Karna

1. Website live ho jaye aur usmein achi content ho jaye (15+ posts, kam se kam 2-4 weeks purani)
2. [google.com/adsense](https://www.google.com/adsense) par jayen aur apply karen
3. Google aap ki site review karega — approval mein 1 din se 3 hafte tak lag sakte hain
4. Approve hone k baad, Google aap ko ek chota sa code dega — wo code har page k `<head>` mein paste karna hai (is website ki har HTML file mein already jagah rakhi hui hai, bas comment wale `ad-slot` divs ko us code se replace kar dena)

## Zaroori Baat

- AdSense approval sirf tab milta hai jab content **original** ho (copy-paste nahi), aur site par kam se kam privacy policy aur about/contact pages hon (ye dono already ban chuke hain)
- Traffic organic search (Google) se aani chahiye — is k liye recipe titles mein wahi words use karen jo log actually search karte hain (jaise "15 minute pasta recipe" na k sirf "pasta")
