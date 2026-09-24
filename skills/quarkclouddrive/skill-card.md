## Description: <br>
夸克网盘官方(Quark Drive)Skill，用于文件上传/下载（支持断点续传）、文件分享与转存、网盘文件搜索、相册整理、AI助手（文件总结与知识问答，支持万级文件）。当用户需要操作夸克网盘文件或进行身份验证时使用。 <br>

This skill is ready for commercial/non-commercial use. <br>

## Publisher: <br>
[quarkdrive](https://clawhub.ai/user/quarkdrive) <br>

### License/Terms of Use: <br>
MIT-0 <br>


## Use Case: <br>
External users and agents use this skill to operate Quark Drive accounts through a command-line workflow, including authentication, file upload and download, sharing, search, photo organization, and file-based AI summary or question answering. <br>

### Deployment Geography for Use: <br>
Global <br>

## Known Risks and Mitigations: <br>
Risk: The installer can make broad local environment and self-update changes. <br>
Mitigation: Review install.sh before installation, prefer installing Node.js independently, and install only when those environment changes are acceptable. <br>
Risk: The skill can upload, move, download, share, and organize cloud-drive content after account authorization. <br>
Mitigation: Confirm user intent before sensitive operations, be careful with public share links, and follow the skill's confirmation rules for update or uninstall requests. <br>


## Reference(s): <br>
- [ClawHub skill page](https://clawhub.ai/quarkdrive/skills/quarkclouddrive) <br>
- [Quark Drive](https://pan.quark.cn) <br>
- [Authorization and account management](references/auth.md) <br>
- [File upload](references/file-upload.md) <br>
- [File operations](references/file-ops.md) <br>
- [File search](references/file-search.md) <br>
- [File sharing](references/file-share.md) <br>
- [Share-link save-as](references/file-saveas.md) <br>
- [Photo organization](references/file-organize.md) <br>
- [Assistant capabilities](references/assistant.md) <br>
- [File reading](references/file-read.md) <br>


## Skill Output: <br>
**Output Type(s):** [text, markdown, shell commands, configuration, guidance] <br>
**Output Format:** [Markdown and shell command guidance, with command results rendered as concise user-facing text or tables.] <br>
**Output Parameters:** [1D] <br>
**Other Properties Related to Output:** [The skill may require account authorization and uses Node.js-based CLI commands to interact with Quark Drive.] <br>

## Skill Version(s): <br>
1.0.4 (source: server release evidence) <br>

## Ethical Considerations: <br>
Users should evaluate whether this skill is appropriate for their environment, review any generated or modified files before relying on them, and apply their organization's safety, security, and compliance requirements before deployment. <br>
