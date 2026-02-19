# paper-xray 📄🔬

An [OpenClaw](https://github.com/nicobailon/openclaw) skill that deconstructs academic papers like an X-ray machine.

## What it does

Instead of summarizing papers, it **dissects** them — extracting core contributions, critical assumptions, hidden logic, and napkin-worthy insights. Output is saved as structured org-mode notes.

## Install

Copy `SKILL.md` into your OpenClaw skills directory.

## Usage

Invoke the skill and provide a paper (PDF path, text, or URL). It will:

1. Strip away academic noise
2. Extract the core insight and key moves
3. Critically examine assumptions and gaps
4. Generate a structured org-mode report saved to `~/Documents/notes/`

## Output

A [denote](https://protesilaos.com/emacs/denote)-compatible org file with:
- Napkin formula & sketch (ASCII art)
- Problem & insight extraction
- Delta vs SOTA
- Critical assumptions & open questions
- Logic flow diagram

## Credits

Based on **ljg-xray-paper** by [lijigang](https://github.com/lijigang). Adapted for OpenClaw with minor modifications.

## License

MIT
