# extension
vscode
 - Auto Close Tag
 - Auto Rename Tag
 - Auto Import
 - Auto Comlete Tag
 - Better Align
 - Better Comments
 - Color Highlight
 - TODO Highlight
 - CSS Peek
 - HTML CSS Support
 - IntelliSense for CSS class names in HTML
 
 - Error Lens
 - Git Extension Pack
 - Hightlight Matching Tag
 
 - JavaScript ES6 code snippet
 - Log File Hightlighter
 - Output Colorizer
 - Project Manager
 - vscode-icons
 - vscode-input-sequence
 
# theme
ayu mirage


# setting.json
{
    "workbench.colorTheme"                  : "Panda Syntax",
    "workbench.iconTheme"                   : "vscode-icons",
    "editor.fontFamily"                     : "'D2Coding light', '나눔스퀘어 네오 OTF Light', Consolas, 'Courier New', monospace",
    "vsicons.dontShowNewVersionMessage"     : true,
    "boot-java.rewrite.reconcile"           : true,
    "editor.bracketPairColorization.enabled": true,
    "editor.guides.bracketPairs"            : "active",
    "git.autofetch"                         : true,
    "java.debug.settings.hotCodeReplace"    : "auto",
    "java.jdt.ls.vmargs":"-Xmx1G",
    "betterAlign.surroundSpace"             : {
        
        "colon": [
            0,
            1
        ],
        "assignment": [
            1,
            1
        ],
        "arrow": [
            1,
            1
        ],
        "comment": 2
    },
    "editor.tokenColorCustomizations": {
        "comments" : "#45f9b4a9"
        // "comments" : "#3DFF92"
    },
    "better-comments.tags": [
    
        {
            "tag": "!",
            "color": "#ff7f7f",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "?",
            "color": "#afc4e7",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "//",
            "color": "#cfc3b5",
            "strikethrough": true,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "todo",
            "color": "#cb9ffd",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "*",
            "color": "#bae7af",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        },
        {
            "tag": "-",
            "color": "#f3cda0",
            "strikethrough": false,
            "underline": false,
            "backgroundColor": "transparent",
            "bold": false,
            "italic": false
        }
    ],
    "java.inlayHints.parameterNames.enabled": "none",
    "files.maxMemoryForLargeFilesMB": 8192,
    "sequence.replaceSelection": true,
    "githubPullRequests.createOnPublishBranch": "never",
    "githubPullRequests.fileListLayout": "tree",
    "security.workspace.trust.untrustedFiles": "open",
}

// # -----------------------------------------------------------------------------
// # Gray Scale
// # -----------------------------------------------------------------------------
// _very-light-gray: '#E6E6E6' # Primary font color
// _very-light-gray-fade: '#FFFFFF'
// _lighter-gray: '#CDCDCD'
// _lighter-gray-fade: '#CDCDCD30'
// _contrast-gray: '#BBBBBB'
// _light-gray: '#757575'
// _light-midnight: '#676B79'
// _steel-gray: '#3E4250'
// _gray: '#373B41'
// _gray-fade: '#373B4199'
// _seal: '#31353a' # Light background
// _very-dark-gray: '#2a2c2d' # Dark background
// _charcoal: '#222223' # Use for borders between gray backgrounds

// # -----------------------------------------------------------------------------
// # Blue+Purple+Green
// # -----------------------------------------------------------------------------
// _blue: '#45A9F9'
// _light-blue: '#6FC1FF'
// _purple: '#B084EB'
// _purple-fade: '#B084EB60'
// _light-purple: '#BCAAFE'
// _green: '#19f9d8'
// _light-green: '#6FE7D2'
// _green-fade: '#19f9d899'
// # -----------------------------------------------------------------------------
// # Pink+Red+Orange
// # -----------------------------------------------------------------------------
// _red: '#FF2C6D'
// _light-red: '#FF4B82'
// _orange: '#FFB86C'
// _light-orange: '#FFCC95'
// _light-orange-fade: '#FFCC9560'
// _pink: '#FF75B5'
// _light-pink: '#FF9AC1'
// _light-pink-fade: '#FF9AC170'
// # -----------------------------------------------------------------------------
// # Element Colors
// # -----------------------------------------------------------------------------
// # Two backgrounds are used to provide contrast between section in editor.
// # Foreground color for normal font, use green for contrast fonts
// _background-dark: '#242526' # very-dark-gray
// _background-light: '#292A2B' # seal
// _foreground: '#E6E6E6' # very-light-gray
// _diff-green: '#19f9d866'
// _diff-red: '#FF4B8266'
// _merge-current-header: '#B084EB90' # purple with alpha
// _merge-current-content: '#B084EB40' # same purple less alpha
// _merge-incoming-header: '#45A9F990' # orange with alpha
// _merge-incoming-content: '#FFB86C40' # same orange less alpha
// _transparent: '#00000000'
// # Git Colors
// _git-modified: '#FFCC95' # light-orange
// _git-added: '#19f9d8' # green
// _git-removed: '#FF4B82' # light-red
// _git-ignored: '#757575' # light-grey
// # Linter Colors
// _error: '#FF4B82' # light-red
// _warning: '#FFCC95' # light-orange
// _info: '#6FC1FF' # light-blue

