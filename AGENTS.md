<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Notes builder

- Chapter notes are authored as Markdown in `tools/notes-builder/chapters/` and converted to branded A4 DOCX by `tools/notes-builder/build-notes.cjs` — keeps every chapter visually identical without manual design work.
- Public study pages share the presentation helpers in `src/components/study-content.tsx` so page hierarchy and content-verification notices stay consistent across the frontend.
