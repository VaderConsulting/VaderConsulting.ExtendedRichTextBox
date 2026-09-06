# VaderConsulting.ExtendedRichTextBox

C#.NET 3.5 WinForms library that subclasses RichTextBox with RichEdit 4.1 (Msftedit), TOM, OLE, printing, and extra formatting. `ExtendedRichTextBox` loads `Msftedit.dll` and uses the `RICHEDIT50W` window class (with a fallback to the stock control if the library is missing), then sets WYSIWYG layout via `EM_SETTARGETDEVICE`. Selection helpers cover underline style and colour, background colour, character style, line spacing, paragraph borders, and numbered or bullet lists; `Print` paginates RTF to a `PrintPageEventArgs`, and OLE helpers insert images, ActiveX (`InsertActiveX`), and other objects. Drag-and-drop of files is handled on the control.

**Source last updated:** 2015-02-13 · **Language:** C# · **Target:** .NET Framework 3.5 · **Output:** class library (`Library`)

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `VaderConsulting.ExtendedRichTextBox` (`VaderConsulting.ExtendedRichTextBox.csproj`) | C# | class library (`net35`, WinForms `Component`) | `ExtendedRichTextBox` control with RichEdit 4.1, TOM/OLE wrappers, printing, and extra character/paragraph formatting. |

## How to open

Open `VaderConsulting.ExtendedRichTextBox.csproj` in Visual Studio 2013 or later (ToolsVersion 12.0). There is no `.sln` in this folder.

## Requirements

- Visual Studio 2013 or later, .NET Framework 3.5

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VaderConsulting.ExtendedRichTextBox`. Assembly title/product `VaderConsulting.ExtendedRichTextBox`; copyright `Copyright ©  2015`; company empty. Namespace `VaderConsulting`. OLE embedding wrappers in `ExtendedRichTextBox.cs` are attributed in-source to Oscar Londoño ([CodeProject MyExtRichTextBox](http://www.codeproject.com/KB/edit/MyExtRichTextBox.aspx)).

## License

MIT © 2026 VaderConsulting. See `LICENSE`.
