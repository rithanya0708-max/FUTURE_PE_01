###Future Interns — Prompt Engineering Task 1
AI Website Copy Generator for Local Businesses

Intern Task ID: FIT/AUG26/PE3802

Repo: FUTURE_PE_01

Business Chosen
Tasty Bites Restaurant — Coimbatore, Tamil Nadu

A local restaurant offering dine-in, takeaway, and home delivery, serving students, families, and office employees.
Why this business: Local restaurants operate in a crowded, low-differentiation market — most homepages sound the same, listing generic phrases like "delicious food" and "great service" without giving customers a real reason to choose them over the next place. Tasty Bites serves three very different audience segments (students, families, office employees) in one venue, making it a strong test case for copy that has to feel personal to multiple reader types at once while staying simple and scannable.

###Tool Used

Claude (claude.ai) — used to design the prompt framework and generate all copy output.

###Prompt Logic

Instead of writing one-off content, this project builds a reusable prompt system — four structured prompt templates, each targeting one part of a business website:
Homepage prompt — generates the restaurant name placement, an engaging headline, a short introduction, service information, standout features, and a call-to-action, tailored to a multi-audience local food business.
Services prompt — generates descriptions for dine-in, takeaway, and home delivery, covering what each service offers and why a customer should pick it.
CTA prompt — generates three CTA types: visit-now, order/delivery-focused, and family/group-booking.
Tone adaptation prompt — a reusable layer that rewrites any base copy into the right tone for a given business type (simple and friendly for restaurants/cafes, professional for clinics/agencies, confident-simple for coaching institutes). This is what makes the system reusable across different clients, not just this one.
Each prompt follows the same structure: Role → Business Context → Task → Rules. The Rules section is what prevents generic AI-sounding output — it explicitly bans vague phrases ("unforgettable experience," "best in town"), fake claims ("award-winning" without proof), and forces concrete, specific details (services offered, target audience, location, atmosphere).
Folder Structure

###Releases

No releases published

Packages

No packages published

Contributors(1)

@rithanya0708-max — rithanya.A
