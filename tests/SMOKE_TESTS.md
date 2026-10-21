# Manual smoke tests
1. Load site through an HTTP static host.
2. Answer prompts and confirm local storage key `capste.v2` updates.
3. Switch Standard / Advanced and verify question count.
4. Verify unsure / not applicable do not score as agreement.
5. Search and filter the library; inspect entries with and without sources.
6. Export and re-import an assessment JSON.
7. Verify similarity, answer coverage and profile coverage are separate.
8. Print results and test keyboard navigation, mobile layout and high contrast.
9. This prototype has not been formally accessibility-audited or psychometrically validated.

## v3 upgrade checks
- Confirm Standard, Advanced and Elite appear in the assessment selector.
- Elite loads 115 questions (85 Advanced + 30 diagnostic follow-ups).
- Check each answer persists after refresh and JSON import/export preserves the selected mode.
- Confirm results show orientation tags and a separate CALCism heuristic panel.
- Confirm BITE review remains a separate practice worksheet and warns against blanket labels.
- Confirm all unanswered/unsure/not-applicable answers remain excluded from numeric similarity.
- Validate on mobile width and with keyboard navigation; a formal accessibility audit remains outstanding.
