# DeSlop for Claude

Create and revise business flyers and posters through your connected DeSlop account. Plan copy in conversation, confirm factual details and the design cost, generate a branded layout, adjust an exact QR code or optional AI label, and export the reviewed PNG or raster PDF.

## Connect and use

Install this plugin in Claude and connect DeSlop from its Connectors tab. Sign in to your own account at https://dslop.app. The connector uses OAuth with S256 PKCE; never enter passwords, API keys or session tokens into a conversation. Claude Code connects to the same remote server through its normal MCP sign-in flow.

Try these prompts:

- “Help me create a café flyer. Draft the copy and ask for essential missing facts before generation.”
- “Open my saved design and move its existing QR code to the bottom right without generating another image.”
- “Export my reviewed flyer as an A4 PDF and explain any resolution warning.”

New generation uses your existing DeSlop allowance or credits and requires confirmation. QR and AI-label placement edits and exports do not start a new image generation. Account limits and prices are shown by the connected service. This integration supports a flyer/poster design workflow, not standalone general image, video or audio generation. It does not purchase credits, change subscriptions or execute payments.

## Files, data and limitations

The skill and MCP configuration are public integration files. The DeSlop application source, user designs and credentials are not included. User-requested design content is sent to the declared DeSlop connector; the skill itself has no scripts, hooks or independent data storage. DeSlop stores account-bound projects and processes confirmed design requests through its providers as described in its privacy policy. Do not import private chat history or unrelated files.

PNG, JPEG and WebP inputs are supported through the editor's upload control. PDF import and direct editing of individual text layers are unsupported. Text/layout revisions require a new confirmed generation. PDF export embeds the current raster and does not create extra resolution, CMYK, bleed or PDF/X. Interactive UI and download behavior depend on the Claude host; the authenticated Studio link remains available for continuation.

If sign-in expires, reconnect DeSlop. If a generation times out, recover the existing job instead of starting another one. Contact support@dslop.app for product or security concerns.

- Website and account: https://dslop.app
- Privacy: https://dslop.app/datenschutz
- Terms: https://dslop.app/agb
- Publisher and support: https://dslop.app/impressum

License: UNLICENSED. All rights reserved. DeSlop service use is governed by its published terms.
