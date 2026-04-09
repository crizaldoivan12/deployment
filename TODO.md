# TODO: Fix TypeScript amount type error for Vercel deploy

## Steps:
- [x] 1. Update DocumentPayload type in `frontend/components/DocumentForm.tsx` (amount: number | null)\n- [x] 2. Update form submit logic to handle null amounts\n- [x] 3. Fix initial amount in `frontend/app/documents/[id]/edit/page.tsx` to docRes.amount ?? null
- [ ] 4. Test build: `cd frontend && npm run build`
- [ ] 5. Redeploy to Vercel
- [ ] 6. Verify edit/create forms functionality

**Status: Code changes complete. Test build below.**

