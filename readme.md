# github-markdown-css

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="github-markdown.css">
<style>
.markdown-body .octicon {
  display: inline-block;
  fill: currentColor;
  vertical-align: text-bottom;
}

.markdown-body .anchor {
  float: left;
  line-height: 1;
  margin-left: 20px;
  padding-right: 4px;
}

.markdown-body .anchor:focus {
  outline: none;
}

.markdown-body h1 .octicon-link,
.markdown-body h2 .octicon-link,
.markdown-body h3 .octicon-link,
.markdown-body h4 .octicon-link,
.markdown-body h5 .octicon-link,
.markdown-body h6 .octicon-link {
  color: #1b1f23;
  vertical-align: middle;
  visibility: hidden;
}

.markdown-body h1:hover .anchor,
.markdown-body h2:hover .anchor,
.markdown-body h3:hover .anchor,
.markdown-body h4:hover .anchor,
.markdown-body h5:hover .anchor,
.markdown-body h6:hover .anchor {
  text-decoration:capitalize;
}

.markdown-body h1:hover .anchor .octicon-link,
.markdown-body h2:hover .anchor .octicon-link,
.markdown-body h3:hover .anchor .octicon-link,
.markdown-body h4:hover .anchor .octicon-link,
.markdown-body h5:hover .anchor .octicon-link,
.markdown-body h6:hover .anchor .octicon-link {
  visibility: visible;
}

.markdown-body h1:hover .anchor .octicon-link:before,
.markdown-body h2:hover .anchor .octicon-link:before,
.markdown-body h3:hover .anchor .octicon-link:before,
.markdown-body h4:hover .anchor .octicon-link:before,
.markdown-body h5:hover .anchor .octicon-link:before,
.markdown-body h6:hover .anchor .octicon-link:before {
  width: 16px;
  height: 16px;
  content: ' ';
  display: inline-block;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' version='1.1' width='16' height='16' aria-hidden='true'%3E%3Cpath fill-rule='evenodd' d='M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z'%3E%3C/path%3E%3C/svg%3E");
}.markdown-body {
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  color: var(--color-text-primary);
  line-height: 1.5;
  word-wrap: break-word;
  font-family: -apple-system,BlinkMacSystemFont,Segoe UI,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji;
  font-size: 16px;
  line-height: 1.5;
  background-color:whitesmoke;
}

.markdown-body :root {
  --border-width: 1px;
  --border-style: solid;
  --font-size-small: 12px;
  --font-weight-semibold: 500;
  --size-2: 20px;
}

.markdown-body details {
  display: block;
}

.markdown-body summary {
  display: list-item;
}

.markdown-body a {
  background-color: whitesmoke;
}

.markdown-body a:active,
.markdown-body a:hover {
  outline-width: 0;
}

.markdown-body strong {
  font-weight: inherit;
  font-weight: bolder;
}

.markdown-body h1 {
  font-size: 2em;
  margin: .67em 0;
}

.markdown-body img {
  border-style: none;
}

.markdown-body code,
.markdown-body kbd,
.markdown-body pre {
  font-family: monospace,monospace;
  font-size: 1em;
}

.markdown-body hr {
  box-sizing: content-box;
  height: 0;
  overflow: visible;
}

.markdown-body input {
  font: inherit;
  margin: 0;
}

.markdown-body input {
  overflow: visible;
}

.markdown-body [type=checkbox] {
  box-sizing: border-box;
  padding: 0;
}

.markdown-body :root {
  --color-scale-black: #1b1f23;
  --color-scale-white: #fff;
  --color-scale-gray-0: #fafbfc;
  --color-scale-gray-1: #f6f8fa;
  --color-scale-gray-2: #e1e4e8;
  --color-scale-gray-3: #d1d5da;
  --color-scale-gray-4: #959da5;
  --color-scale-gray-5: #6a737d;
  --color-scale-gray-6: #586069;
  --color-scale-gray-7: #444d56;
  --color-scale-gray-8: #2f363d;
  --color-scale-gray-9: #24292e;
  --color-scale-blue-0: #f1f8ff;
  --color-scale-blue-1: #dbedff;
  --color-scale-blue-2: #c8e1ff;
  --color-scale-blue-3: #79b8ff;
  --color-scale-blue-4: #2188ff;
  --color-scale-blue-5: #0366d6;
  --color-scale-blue-6: #005cc5;
  --color-scale-blue-7: #044289;
  --color-scale-blue-8: #032f62;
  --color-scale-blue-9: #05264c;
  --color-scale-green-0: #f0fff4;
  --color-scale-green-1: #dcffe4;
  --color-scale-green-2: #bef5cb;
  --color-scale-green-3: #85e89d;
  --color-scale-green-4: #34d058;
  --color-scale-green-5: #28a745;
  --color-scale-green-6: #22863a;
  --color-scale-green-7: #176f2c;
  --color-scale-green-8: #165c26;
  --color-scale-green-9: #144620;
  --color-scale-yellow-0: #fffdef;
  --color-scale-yellow-1: #fffbdd;
  --color-scale-yellow-2: #fff5b1;
  --color-scale-yellow-3: #ffea7f;
  --color-scale-yellow-4: #ffdf5d;
  --color-scale-yellow-5: #ffd33d;
  --color-scale-yellow-6: #f9c513;
  --color-scale-yellow-7: #dbab09;
  --color-scale-yellow-8: #b08800;
  --color-scale-yellow-9: #735c0f;
  --color-scale-orange-0: #fff8f2;
  --color-scale-orange-1: #ffebda;
  --color-scale-orange-2: #ffd1ac;
  --color-scale-orange-3: #ffab70;
  --color-scale-orange-4: #fb8532;
  --color-scale-orange-5: #f66a0a;
  --color-scale-orange-6: #e36209;
  --color-scale-orange-7: #d15704;
  --color-scale-orange-8: #c24e00;
  --color-scale-orange-9: #a04100;
  --color-scale-red-0: #ffeef0;
  --color-scale-red-1: #ffdce0;
  --color-scale-red-2: #fdaeb7;
  --color-scale-red-3: #f97583;
  --color-scale-red-4: #ea4a5a;
  --color-scale-red-5: #d73a49;
  --color-scale-red-6: #cb2431;
  --color-scale-red-7: #b31d28;
  --color-scale-red-8: #9e1c23;
  --color-scale-red-9: #86181d;
  --color-scale-purple-0: #f5f0ff;
  --color-scale-purple-1: #e6dcfd;
  --color-scale-purple-2: #d1bcf9;
  --color-scale-purple-3: #b392f0;
  --color-scale-purple-4: #8a63d2;
  --color-scale-purple-5: #6f42c1;
  --color-scale-purple-6: #5a32a3;
  --color-scale-purple-7: #4c2889;
  --color-scale-purple-8: #3a1d6e;
  --color-scale-purple-9: #29134e;
  --color-scale-pink-0: #ffeef8;
  --color-scale-pink-1: #fedbf0;
  --color-scale-pink-2: #f9b3dd;
  --color-scale-pink-3: #f692ce;
  --color-scale-pink-4: #ec6cb9;
  --color-scale-pink-5: #ea4aaa;
  --color-scale-pink-6: #d03592;
  --color-scale-pink-7: #b93a86;
  --color-scale-pink-8: #99306f;
  --color-scale-pink-9: #6d224f;
  --color-auto-black: #1b1f23;
  --color-auto-white: #fff;
  --color-auto-gray-0: #fafbfc;
  --color-auto-gray-1: #f6f8fa;
  --color-auto-gray-2: #e1e4e8;
  --color-auto-gray-3: #d1d5da;
  --color-auto-gray-4: #959da5;
  --color-auto-gray-5: #6a737d;
  --color-auto-gray-6: #586069;
  --color-auto-gray-7: #444d56;
  --color-auto-gray-8: #2f363d;
  --color-auto-gray-9: #24292e;
  --color-auto-blue-0: #f1f8ff;
  --color-auto-blue-1: #dbedff;
  --color-auto-blue-2: #c8e1ff;
  --color-auto-blue-3: #79b8ff;
  --color-auto-blue-4: #2188ff;
  --color-auto-blue-5: #0366d6;
  --color-auto-blue-6: #005cc5;
  --color-auto-blue-7: #044289;
  --color-auto-blue-8: #032f62;
  --color-auto-blue-9: #05264c;
  --color-auto-green-0: #f0fff4;
  --color-auto-green-1: #dcffe4;
  --color-auto-green-2: #bef5cb;
  --color-auto-green-3: #85e89d;
  --color-auto-green-4: #34d058;
  --color-auto-green-5: #28a745;
  --color-auto-green-6: #22863a;
  --color-auto-green-7: #176f2c;
  --color-auto-green-8: #165c26;
  --color-auto-green-9: #144620;
  --color-auto-yellow-0: #fffdef;
  --color-auto-yellow-1: #fffbdd;
  --color-auto-yellow-2: #fff5b1;
  --color-auto-yellow-3: #ffea7f;
  --color-auto-yellow-4: #ffdf5d;
  --color-auto-yellow-5: #ffd33d;
  --color-auto-yellow-6: #f9c513;
  --color-auto-yellow-7: #dbab09;
  --color-auto-yellow-8: #b08800;
  --color-auto-yellow-9: #735c0f;
  --color-auto-orange-0: #fff8f2;
  --color-auto-orange-1: #ffebda;
  --color-auto-orange-2: #ffd1ac;
  --color-auto-orange-3: #ffab70;
  --color-auto-orange-4: #fb8532;
  --color-auto-orange-5: #f66a0a;
  --color-auto-orange-6: #e36209;
  --color-auto-orange-7: #d15704;
  --color-auto-orange-8: #c24e00;
  --color-auto-orange-9: #a04100;
  --color-auto-red-0: #ffeef0;
  --color-auto-red-1: #ffdce0;
  --color-auto-red-2: #fdaeb7;
  --color-auto-red-3: #f97583;
  --color-auto-red-4: #ea4a5a;
  --color-auto-red-5: #d73a49;
  --color-auto-red-6: #cb2431;
  --color-auto-red-7: #b31d28;
  --color-auto-red-8: #9e1c23;
  --color-auto-red-9: #86181d;
  --color-auto-purple-0: #f5f0ff;
  --color-auto-purple-1: #e6dcfd;
  --color-auto-purple-2: #d1bcf9;
  --color-auto-purple-3: #b392f0;
  --color-auto-purple-4: #8a63d2;
  --color-auto-purple-5: #6f42c1;
  --color-auto-purple-6: #5a32a3;
  --color-auto-purple-7: #4c2889;
  --color-auto-purple-8: #3a1d6e;
  --color-auto-purple-9: #29134e;
  --color-auto-pink-0: #ffeef8;
  --color-auto-pink-1: #fedbf0;
  --color-auto-pink-2: #f9b3dd;
  --color-auto-pink-3: #f692ce;
  --color-auto-pink-4: #ec6cb9;
  --color-auto-pink-5: #ea4aaa;
  --color-auto-pink-6: #d03592;
  --color-auto-pink-7: #b93a86;
  --color-auto-pink-8: #99306f;
  --color-auto-pink-9: #6d224f;
  --color-text-primary: #24292e;
  --color-text-secondary: #586069;
  --color-text-tertiary: #6a737d;
  --color-text-placeholder: #6a737d;
  --color-text-disabled: #959da5;
  --color-text-inverse: #fff;
  --color-text-link: #0366d6;
  --color-text-danger: #cb2431;
  --color-text-success: #22863a;
  --color-text-warning: #b08800;
  --color-text-white: #fff;
  --color-icon-primary: #24292e;
  --color-icon-secondary: #586069;
  --color-icon-tertiary: #959da5;
  --color-icon-info: #0366d6;
  --color-icon-danger: #d73a49;
  --color-icon-success: #22863a;
  --color-icon-warning: #b08800;
  --color-border-primary: #e1e4e8;
  --color-border-secondary: #ebedef;
  --color-border-tertiary: #d1d5da;
  --color-border-overlay: #e1e4e8;
  --color-border-inverse: #fff;
  --color-border-info: #0366d6;
  --color-border-danger: #d73a49;
  --color-border-success: #34d058;
  --color-border-warning: #f9c513;
  --color-bg-canvas: #fff;
  --color-bg-canvas-mobile: #fff;
  --color-bg-canvas-inverse: #24292e;
  --color-bg-canvas-inset: #f6f8fa;
  --color-bg-primary: #fff;
  --color-bg-secondary: #fafbfc;
  --color-bg-tertiary: #f6f8fa;
  --color-bg-overlay: #fff;
  --color-bg-backdrop: rgba(27,31,35,0.5);
  --color-bg-info: #f1f8ff;
  --color-bg-info-inverse: #0366d6;
  --color-bg-danger: #ffeef0;
  --color-bg-danger-inverse: #d73a49;
  --color-bg-success: #dcffe4;
  --color-bg-success-inverse: #28a745;
  --color-bg-warning: #fff5b1;
  --color-bg-warning-inverse: #ffd33d;
  --color-shadow-small: 0 1px 0 rgba(27,31,35,0.04);
  --color-shadow-medium: 0 3px 6px rgba(149,157,165,0.15);
  --color-shadow-large: 0 8px 24px rgba(149,157,165,0.2);
  --color-shadow-extra-large: 0 12px 48px rgba(149,157,165,0.3);
  --color-shadow-highlight: inset 0 1px 0 rgba(255,255,255,0.25);
  --color-shadow-inset: inset 0 1px 0 rgba(225,228,232,0.2);
  --color-state-hover-primary-bg: #0366d6;
  --color-state-hover-primary-border: #0366d6;
  --color-state-hover-primary-text: #fff;
  --color-state-hover-primary-icon: #fff;
  --color-state-hover-secondary-bg: #f6f8fa;
  --color-state-hover-secondary-border: #f6f8fa;
  --color-state-selected-primary-bg: #0366d6;
  --color-state-selected-primary-border: #0366d6;
  --color-state-selected-primary-text: #fff;
  --color-state-selected-primary-icon: #fff;
  --color-state-focus-border: #0366d6;
  --color-state-focus-shadow: 0 0 0 3px rgba(3,102,214,0.3);
  --color-fade-fg-10: rgba(27,31,35,0.1);
  --color-fade-fg-15: rgba(27,31,35,0.15);
  --color-fade-fg-30: rgba(27,31,35,0.3);
  --color-fade-fg-50: rgba(27,31,35,0.5);
  --color-fade-fg-70: rgba(27,31,35,0.7);
  --color-fade-fg-85: rgba(27,31,35,0.85);
  --color-fade-black-10: rgba(27,31,35,0.1);
  --color-fade-black-15: rgba(27,31,35,0.15);
  --color-fade-black-30: rgba(27,31,35,0.3);
  --color-fade-black-50: rgba(27,31,35,0.5);
  --color-fade-black-70: rgba(27,31,35,0.7);
  --color-fade-black-85: rgba(27,31,35,0.85);
  --color-fade-white-10: rgba(255,255,255,0.1);
  --color-fade-white-15: rgba(255,255,255,0.15);
  --color-fade-white-30: rgba(255,255,255,0.3);
  --color-fade-white-50: rgba(255,255,255,0.5);
  --color-fade-white-70: rgba(255,255,255,0.7);
  --color-fade-white-85: rgba(255,255,255,0.85);
  --color-alert-info-text: #24292e;
  --color-alert-info-icon: rgba(4,66,137,0.6);
  --color-alert-info-bg: #dbedff;
  --color-alert-info-border: rgba(4,66,137,0.2);
  --color-alert-warn-text: #24292e;
  --color-alert-warn-icon: #b08800;
  --color-alert-warn-bg: #fffbdd;
  --color-alert-warn-border: rgba(176,136,0,0.2);
  --color-alert-error-text: #24292e;
  --color-alert-error-icon: rgba(158,28,35,0.6);
  --color-alert-error-bg: #ffe3e6;
  --color-alert-error-border: rgba(158,28,35,0.2);
  --color-alert-success-text: #24292e;
  --color-alert-success-icon: rgba(23,111,44,0.8);
  --color-alert-success-bg: #dcffe4;
  --color-alert-success-border: rgba(23,111,44,0.2);
  --color-autocomplete-shadow: 0 3px 6px rgba(149,157,165,0.15);
  --color-autocomplete-row-border: #ebedef;
  --color-blankslate-icon: #757f8a;
  --color-btn-text: #24292e;
  --color-btn-bg: #fafbfc;
  --color-btn-border: rgba(27,31,35,0.15);
  --color-btn-shadow: 0 1px 0 rgba(27,31,35,0.04);
  --color-btn-inset-shadow: inset 0 1px 0 rgba(255,255,255,0.25);
  --color-btn-hover-bg: #f3f4f6;
  --color-btn-hover-border: rgba(27,31,35,0.15);
  --color-btn-active-bg: #ebecf0;
  --color-btn-active-border: rgba(27,31,35,0.1);
  --color-btn-selected-bg: #eeeff2;
  --color-btn-focus-bg: #fafbfc;
  --color-btn-focus-border: rgba(27,31,35,0.15);
  --color-btn-focus-shadow: 0 0 0 3px rgba(3,102,214,0.3);
  --color-btn-shadow-active: inset 0 0.15em 0.3em rgba(27,31,35,0.15);
  --color-btn-shadow-input-focus: 0 0 0 0.2em rgba(3,102,214,0.3);
  --color-btn-counter-bg: rgba(27,31,35,0.08);
  --color-btn-primary-text: #fff;
  --color-btn-primary-bg: #2ea44f;
  --color-btn-primary-border: rgba(27,31,35,0.15);
  --color-btn-primary-shadow: 0 1px 0 rgba(27,31,35,0.1);
  --color-btn-primary-inset-shadow: inset 0 1px 0 rgba(255,255,255,0.03);
  --color-btn-primary-hover-bg: #2c974b;
  --color-btn-primary-hover-border: rgba(27,31,35,0.15);
  --color-btn-primary-selected-bg: #298e46;
  --color-btn-primary-selected-shadow: inset 0 1px 0 rgba(20,70,32,0.2);
  --color-btn-primary-disabled-text: rgba(255,255,255,0.8);
  --color-btn-primary-disabled-bg: #94d3a2;
  --color-btn-primary-disabled-border: rgba(27,31,35,0.1);
  --color-btn-primary-focus-bg: #2ea44f;
  --color-btn-primary-focus-border: rgba(27,31,35,0.15);
  --color-btn-primary-focus-shadow: 0 0 0 3px rgba(46,164,79,0.4);
  --color-btn-primary-icon: rgba(255,255,255,0.8);
  --color-btn-primary-counter-bg: rgba(255,255,255,0.2);
  --color-btn-outline-text: #0366d6;
  --color-btn-outline-hover-text: #fff;
  --color-btn-outline-hover-bg: #0366d6;
  --color-btn-outline-hover-border: rgba(27,31,35,0.15);
  --color-btn-outline-hover-shadow: 0 1px 0 rgba(27,31,35,0.1);
  --color-btn-outline-hover-inset-shadow: inset 0 1px 0 rgba(255,255,255,0.03);
  --color-btn-outline-hover-counter-bg: rgba(255,255,255,0.2);
  --color-btn-outline-selected-text: #fff;
  --color-btn-outline-selected-bg: #035fc9;
  --color-btn-outline-selected-border: rgba(27,31,35,0.15);
  --color-btn-outline-selected-shadow: inset 0 1px 0 rgba(5,38,76,0.2);
  --color-btn-outline-disabled-text: rgba(3,102,214,0.5);
  --color-btn-outline-disabled-bg: #fafbfc;
  --color-btn-outline-disabled-counter-bg: rgba(3,102,214,0.05);
  --color-btn-outline-focus-border: rgba(27,31,35,0.15);
  --color-btn-outline-focus-shadow: 0 0 0 3px rgba(0,92,197,0.4);
  --color-btn-outline-counter-bg: rgba(3,102,214,0.1);
  --color-btn-danger-text: #d73a49;
  --color-btn-danger-hover-text: #fff;
  --color-btn-danger-hover-bg: #cb2431;
  --color-btn-danger-hover-border: rgba(27,31,35,0.15);
  --color-btn-danger-hover-shadow: 0 1px 0 rgba(27,31,35,0.1);
  --color-btn-danger-hover-inset-shadow: inset 0 1px 0 rgba(255,255,255,0.03);
  --color-btn-danger-hover-counter-bg: rgba(255,255,255,0.2);
  --color-btn-danger-selected-text: #fff;
  --color-btn-danger-selected-bg: #d53040;
  --color-btn-danger-selected-border: rgba(27,31,35,0.15);
  --color-btn-danger-selected-shadow: inset 0 1px 0 rgba(134,24,29,0.2);
  --color-btn-danger-disabled-text: rgba(215,58,73,0.5);
  --color-btn-danger-disabled-bg: #fafbfc;
  --color-btn-danger-disabled-counter-bg: rgba(215,58,73,0.05);
  --color-btn-danger-focus-border: rgba(27,31,35,0.15);
  --color-btn-danger-focus-shadow: 0 0 0 3px rgba(203,36,49,0.4);
  --color-btn-danger-counter-bg: rgba(215,58,73,0.1);
  --color-btn-danger-icon: #d73a49;
  --color-btn-danger-hover-icon: #fff;
  --color-counter-text: #24292e;
  --color-counter-bg: rgba(209,213,218,0.5);
  --color-counter-primary-text: #fff;
  --color-counter-primary-bg: #6a737d;
  --color-counter-secondary-text: #6a737d;
  --color-counter-secondary-bg: rgba(209,213,218,0.5);
  --color-dropdown-shadow: 0 8px 24px rgba(149,157,165,0.2);
  --color-overlay-shadow: 0 1px 3px rgba(27,31,35,0.12),0 8px 24px rgba(68,77,86,0.12);
  --color-label-border: #e1e4e8;
  --color-label-primary-text: #24292e;
  --color-label-primary-border: #6a737d;
  --color-label-secondary-text: #586069;
  --color-label-secondary-border: #e1e4e8;
  --color-label-info-text: #0366d6;
  --color-label-info-border: #0366d6;
  --color-label-success-text: #22863a;
  --color-label-success-border: #28a745;
  --color-label-warning-text: #735c0f;
  --color-label-warning-border: #b08800;
  --color-label-danger-text: #d73a49;
  --color-label-danger-border: #cb2431;
  --color-label-orange-text: #c24e00;
  --color-label-orange-border: #f66a0a;
  --color-input-bg: #fff;
  --color-input-contrast-bg: #fafbfc;
  --color-input-border: #e1e4e8;
  --color-input-shadow: inset 0 1px 2px rgba(27,31,35,0.075);
  --color-input-disabled-bg: #f6f8fa;
  --color-input-disabled-border: #e1e4e8;
  --color-input-warning-border: #f9c513;
  --color-input-error-border: #cb2431;
  --color-input-tooltip-success-text: #144620;
  --color-input-tooltip-success-bg: #dcffe4;
  --color-input-tooltip-success-border: #34d058;
  --color-input-tooltip-warning-text: #735c0f;
  --color-input-tooltip-warning-bg: #fff5b1;
  --color-input-tooltip-warning-border: #f9c513;
  --color-input-tooltip-error-text: #86181d;
  --color-input-tooltip-error-bg: #ffeef0;
  --color-input-tooltip-error-border: #f97583;
  --color-avatar-bg: #fff;
  --color-avatar-border: transparent;
  --color-avatar-stack-fade: #d1d5da;
  --color-avatar-stack-fade-more: #e1e4e8;
  --color-avatar-child-shadow: -2px -2px 0 rgba(255,255,255,0.8);
  --color-toast-text: #24292e;
  --color-toast-bg: #fff;
  --color-toast-border: #e1e4e8;
  --color-toast-shadow: 0 8px 24px rgba(149,157,165,0.2);
  --color-toast-icon: #fff;
  --color-toast-icon-bg: #0366d6;
  --color-toast-icon-border: transparent;
  --color-toast-success-text: #24292e;
  --color-toast-success-border: #e1e4e8;
  --color-toast-success-icon: #fff;
  --color-toast-success-icon-bg: #28a745;
  --color-toast-success-icon-border: transparent;
  --color-toast-warning-text: #24292e;
  --color-toast-warning-border: #e1e4e8;
  --color-toast-warning-icon: #24292e;
  --color-toast-warning-icon-bg: #ffd33d;
  --color-toast-warning-icon-border: transparent;
  --color-toast-danger-text: #24292e;
  --color-toast-danger-border: #e1e4e8;
  --color-toast-danger-icon: #fff;
  --color-toast-danger-icon-bg: #d73a49;
  --color-toast-danger-icon-border: transparent;
  --color-toast-loading-text: #24292e;
  --color-toast-loading-border: #e1e4e8;
  --color-toast-loading-icon: #fff;
  --color-toast-loading-icon-bg: #586069;
  --color-toast-loading-icon-border: transparent;
  --color-timeline-text: #444d56;
  --color-timeline-badge-bg: #e1e4e8;
  --color-timeline-badge-success-border: transparent;
  --color-timeline-target-badge-border: #2188ff;
  --color-timeline-target-badge-shadow: #c8e1ff;
  --color-select-menu-border-secondary: #ebedef;
  --color-select-menu-shadow: 0 0 18px rgba(27,31,35,0.4);
  --color-select-menu-backdrop-bg: rgba(27,31,35,0.5);
  --color-select-menu-backdrop-border: transparent;
  --color-select-menu-tap-highlight: rgba(209,213,218,0.5);
  --color-select-menu-tap-focus-bg: #dbedff;
  --color-box-blue-border: #c8e1ff;
  --color-box-row-yellow-bg: #fffbdd;
  --color-box-row-blue-bg: #f1f8ff;
  --color-box-header-blue-bg: #f1f8ff;
  --color-box-header-blue-border: #c8e1ff;
  --color-box-border-info: rgba(3,102,214,0.2);
  --color-box-bg-info: #f1f8ff;
  --color-box-border-warning: rgba(255,211,61,0.4);
  --color-box-bg-warning: #fffdef;
  --color-branch-name-text: #586069;
  --color-branch-name-icon: #a9bbd1;
  --color-branch-name-bg: #ebf5ff;
  --color-branch-name-link-text: #0366d6;
  --color-branch-name-link-icon: #a9bbd1;
  --color-branch-name-link-bg: #ebf5ff;
  --color-markdown-code-bg: rgba(27,31,35,0.05);
  --color-markdown-frame-border: #e0e3e6;
  --color-markdown-blockquote-border: #e0e3e6;
  --color-markdown-table-border: #e0e3e6;
  --color-markdown-table-tr-border: #c6cbd2;
  --color-menu-heading-text: #24292e;
  --color-menu-border-active: #f9826c;
  --color-menu-bg-active: transparent;
  --color-sidenav-selected-bg: #fff;
  --color-sidenav-border-active: #f9826c;
  --color-header-text: rgba(255,255,255,0.7);
  --color-header-bg: #24292e;
  --color-header-logo: #fff;
  --color-filter-item-bar-bg: #eff2f6;
  --color-hidden-text-expander-bg: #e0e3e6;
  --color-hidden-text-expander-bg-hover: #c6cbd2;
  --color-drag-and-drop-border: #c4c9cf;
  --color-upload-enabled-border: #e0e3e6;
  --color-upload-enabled-border-focused: #479dff;
  --color-previewable-comment-form-border: #c4c9cf;
  --color-underlinenav-border: rgba(209,213,218,0);
  --color-underlinenav-border-hover: #d1d5da;
  --color-underlinenav-border-active: #f9826c;
  --color-underlinenav-text: #24292e;
  --color-underlinenav-text-hover: #24292e;
  --color-underlinenav-text-active: #24292e;
  --color-underlinenav-icon: #959da5;
  --color-underlinenav-icon-hover: #959da5;
  --color-underlinenav-icon-active: #24292e;
  --color-underlinenav-counter-text: #24292e;
  --color-underlinenav-counter-bg: rgba(209,213,218,0.5);
  --color-verified-badge-text: #22863a;
  --color-verified-badge-bg: #fff;
  --color-verified-badge-border: #e1e4e8;
  --color-social-count-bg: #fff;
  --color-tooltip-text: #fff;
  --color-tooltip-bg: #24292e;
  --color-header-search-bg: #24292e;
  --color-header-search-border: #444d56;
  --color-search-keyword-hl: #fffbdd;
  --color-diffstat-neutral-bg: #d1d5da;
  --color-diffstat-neutral-border: #d1d5da;
  --color-diffstat-deletion-bg: #d73a49;
  --color-diffstat-deletion-border: #d73a49;
  --color-diffstat-addition-bg: #28a745;
  --color-diffstat-addition-border: #28a745;
  --color-mktg-success: #2ebc4f;
  --color-mktg-info: #1074e7;
  --color-mktg-bg-shade-gradient-top: rgba(27,31,35,0.065);
  --color-mktg-bg-shade-gradient-bottom: rgba(27,31,35,0);
  --color-mktg-btn-bg-top: #617eef;
  --color-mktg-btn-bg-bottom: #4969ed;
  --color-mktg-btn-bg-overlay-top: #4968e4;
  --color-mktg-btn-bg-overlay-bottom: #3355e0;
  --color-mktg-btn-text: #fff;
  --color-mktg-btn-primary-bg-top: #34b759;
  --color-mktg-btn-primary-bg-bottom: #2ea44f;
  --color-mktg-btn-primary-bg-overlay-top: #279b42;
  --color-mktg-btn-primary-bg-overlay-bottom: #22863a;
  --color-mktg-btn-primary-text: #fff;
  --color-mktg-btn-enterprise-bg-top: #8670ff;
  --color-mktg-btn-enterprise-bg-bottom: #6f57ff;
  --color-mktg-btn-enterprise-bg-overlay-top: #7463de;
  --color-mktg-btn-enterprise-bg-overlay-bottom: #614eda;
  --color-mktg-btn-enterprise-text: #fff;
  --color-mktg-btn-outline-text: #4969ed;
  --color-mktg-btn-outline-border: rgba(73,105,237,0.3);
  --color-mktg-btn-outline-hover-text: #3355e0;
  --color-mktg-btn-outline-hover-border: rgba(51,85,224,0.5);
  --color-mktg-btn-outline-focus-border: #4969ed;
  --color-mktg-btn-outline-focus-border-inset: rgba(73,105,237,0.5);
  --color-mktg-btn-dark-text: #fff;
  --color-mktg-btn-dark-border: rgba(255,255,255,0.3);
  --color-mktg-btn-dark-hover-text: #fff;
  --color-mktg-btn-dark-hover-border: rgba(255,255,255,0.5);
  --color-mktg-btn-dark-focus-border: #fff;
  --color-mktg-btn-dark-focus-border-inset: rgba(255,255,255,0.5);
  --color-files-explorer-icon: #79b8ff;
  --color-hl-author-bg: #f1f8ff;
  --color-hl-author-border: #c8e1ff;
  --color-logo-subdued: #d1d5da;
  --color-discussion-border: #a4ccae;
  --color-discussion-bg-success: #28a745;
  --color-actions-workflow-table-sticky-bg: rgba(255,255,255,0.95);
  --color-repo-language-color-border: rgba(27,31,35,0.1);
  --color-code-selection-bg: #c8e1ff;
  --color-highlight-text: #442c12;
  --color-highlight-bg: #fff0bb;
  --color-blob-line-highlight-bg: #fffbdd;
  --color-blob-line-highlight-border: transparent;
  --color-diff-addition-text: #22863a;
  --color-diff-addition-bg: #e6ffec;
  --color-diff-addition-border: #34d058;
  --color-diff-deletion-text: #cb2431;
  --color-diff-deletion-bg: #ffeef0;
  --color-diff-deletion-border: #d73a49;
  --color-diff-change-text: #b08800;
  --color-diff-change-bg: #fff5b1;
  --color-diff-change-border: #f9c513;
  --color-diff-blob-num-text: rgba(27,31,35,0.3);
  --color-diff-blob-num-hover-text: rgba(27,31,35,0.6);
  --color-diff-blob-addition-num-text: rgba(27,31,35,0.3);
  --color-diff-blob-addition-num-hover-text: rgba(27,31,35,0.6);
  --color-diff-blob-addition-num-bg: #ccffd8;
  --color-diff-blob-addition-line-bg: #e6ffec;
  --color-diff-blob-addition-word-bg: #abf2bc;
  --color-diff-blob-deletion-num-text: rgba(27,31,35,0.3);
  --color-diff-blob-deletion-num-hover-text: rgba(27,31,35,0.6);
  --color-diff-blob-deletion-num-bg: #ffdce0;
  --color-diff-blob-deletion-line-bg: #ffeef0;
  --color-diff-blob-deletion-word-bg: #fdb9c1;
  --color-diff-blob-hunk-text: rgba(27,31,35,0.7);
  --color-diff-blob-hunk-num-bg: #dbedff;
  --color-diff-blob-hunk-line-bg: #f1f8ff;
  --color-diff-blob-empty-block-bg: #fafbfc;
  --color-diff-blob-selected-line-highlight-bg: rgba(255,223,93,0.2);
  --color-diff-blob-selected-line-highlight-border: #ffd33d;
  --color-diff-blob-selected-line-highlight-mix-blend-mode: multiply;
  --color-diff-blob-expander-icon: #586069;
  --color-diff-blob-expander-hover-icon: #fff;
  --color-diff-blob-expander-hover-bg: #0366d6;
  --color-diff-blob-comment-button-icon: #fff;
  --color-diff-blob-comment-button-bg: #0366d6;
  --color-diff-blob-comment-button-gradient-bg: #0472f1;
  --color-global-nav-logo: #fff;
  --color-global-nav-bg: #24292e;
  --color-global-nav-text: #fff;
  --color-global-nav-icon: #fff;
  --color-global-nav-input-bg: #fafbfc;
  --color-global-nav-input-border: #fafbfc;
  --color-global-nav-input-icon: #d1d5da;
  --color-global-nav-input-placeholder: #959da5;
  --color-footer-invertocat-octicon: #d1d5da;
  --color-footer-invertocat-octicon-hover: #6a737d;
  --color-pr-state-draft-text: #fff;
  --color-pr-state-draft-bg: #6a737d;
  --color-pr-state-draft-border: transparent;
  --color-pr-state-open-text: #fff;
  --color-pr-state-open-bg: #28a745;
  --color-pr-state-open-border: transparent;
  --color-pr-state-merged-text: #fff;
  --color-pr-state-merged-bg: #6f42c1;
  --color-pr-state-merged-border: transparent;
  --color-pr-state-closed-text: #fff;
  --color-pr-state-closed-bg: #d73a49;
  --color-pr-state-closed-border: transparent;
  --color-topic-tag-text: #0366d6;
  --color-topic-tag-bg: #f1f8ff;
  --color-topic-tag-hover-bg: #dbedff;
  --color-topic-tag-active-bg: #e6f2ff;
  --color-merge-box-success-icon-bg: #28a745;
  --color-merge-box-success-icon-text: #fff;
  --color-merge-box-success-icon-border: transparent;
  --color-merge-box-success-indicator-bg: #28a745;
  --color-merge-box-success-indicator-border: transparent;
  --color-merge-box-merged-icon-bg: #6f42c1;
  --color-merge-box-merged-icon-text: #fff;
  --color-merge-box-merged-icon-border: transparent;
  --color-merge-box-merged-box-border: #6f42c1;
  --color-merge-box-neutral-icon-bg: #6a737d;
  --color-merge-box-neutral-icon-text: #fff;
  --color-merge-box-neutral-icon-border: transparent;
  --color-merge-box-neutral-indicator-bg: #6a737d;
  --color-merge-box-neutral-indicator-border: transparent;
  --color-merge-box-warning-icon-bg: #dbab09;
  --color-merge-box-warning-icon-text: #fff;
  --color-merge-box-warning-icon-border: transparent;
  --color-merge-box-warning-box-border: #ffd33d;
  --color-merge-box-warning-merge-highlight: transparent;
  --color-merge-box-error-icon-bg: #d73a49;
  --color-merge-box-error-icon-text: #fff;
  --color-merge-box-error-icon-border: transparent;
  --color-merge-box-error-indicator-bg: #d73a49;
  --color-merge-box-error-indicator-border: transparent;
  --color-project-card-bg: #fff;
  --color-project-header-bg: #24292e;
  --color-project-sidebar-bg: #fff;
  --color-project-gradient-in: #fff;
  --color-project-gradient-out: rgba(255,255,255,0);
  --color-checks-bg: #24292e;
  --color-checks-run-border-width: 0px;
  --color-checks-container-border-width: 0px;
  --color-checks-text-primary: #fafbfc;
  --color-checks-text-secondary: #959da5;
  --color-checks-text-link: #79b8ff;
  --color-checks-btn-icon: #d1d5da;
  --color-checks-btn-hover-icon: #fafbfc;
  --color-checks-btn-hover-bg: rgba(255,255,255,0.125);
  --color-checks-input-text: #f6f8fa;
  --color-checks-input-placeholder-text: #959da5;
  --color-checks-input-focus-text: #959da5;
  --color-checks-input-bg: #2f363d;
  --color-checks-input-shadow: none;
  --color-checks-donut-error: #cb2431;
  --color-checks-donut-pending: #dbab09;
  --color-checks-donut-success: #28a745;
  --color-checks-donut-neutral: #959da5;
  --color-checks-dropdown-text: #d1d5da;
  --color-checks-dropdown-bg: #2f363d;
  --color-checks-dropdown-border: #444d56;
  --color-checks-dropdown-hover-text: #fafbfc;
  --color-checks-dropdown-hover-bg: #444d56;
  --color-checks-dropdown-btn-hover-text: #fafbfc;
  --color-checks-dropdown-btn-hover-bg: #2f363d;
  --color-checks-scrollbar-thumb-bg: #586069;
  --color-checks-header-label-text: #e1e4e8;
  --color-checks-header-label-open-text: #fafbfc;
  --color-checks-header-border: #2f363d;
  --color-checks-header-icon: #959da5;
  --color-checks-line-text: #e1e4e8;
  --color-checks-line-num-text: rgba(149,157,165,0.75);
  --color-checks-line-timestamp-text: #959da5;
  --color-checks-line-hover-bg: #2f363d;
  --color-checks-line-selected-bg: rgba(33,136,255,0.15);
  --color-checks-line-selected-num-text: #79b8ff;
  --color-checks-line-dt-fm-text: #24292e;
  --color-checks-line-dt-fm-bg: #ffd33d;
  --color-checks-gate-bg: rgba(249,197,19,0.15);
  --color-checks-gate-text: #e1e4e8;
  --color-checks-gate-waiting-text: #d1d5da;
  --color-checks-step-header-open-bg: #2f363d;
  --color-checks-step-error-text: #f97583;
  --color-checks-step-warning-text: #ffea7f;
  --color-checks-logline-text: #959da5;
  --color-checks-logline-num-text: rgba(149,157,165,0.75);
  --color-checks-logline-debug-text: #b392f0;
  --color-checks-logline-error-text: #e1e4e8;
  --color-checks-logline-error-num-text: #f97583;
  --color-checks-logline-error-bg: rgba(203,36,49,0.15);
  --color-checks-logline-warning-text: #e1e4e8;
  --color-checks-logline-warning-num-text: #ffea7f;
  --color-checks-logline-warning-bg: rgba(249,197,19,0.15);
  --color-checks-logline-command-text: #79b8ff;
  --color-checks-logline-section-text: #85e89d;
  --color-checks-ansi-black: #24292e;
  --color-checks-ansi-black-bright: #2f363d;
  --color-checks-ansi-white: #e1e4e8;
  --color-checks-ansi-white-bright: #e1e4e8;
  --color-checks-ansi-gray: #959da5;
  --color-checks-ansi-red: #f97583;
  --color-checks-ansi-red-bright: #fdaeb7;
  --color-checks-ansi-green: #85e89d;
  --color-checks-ansi-green-bright: #bef5cb;
  --color-checks-ansi-yellow: #ffea7f;
  --color-checks-ansi-yellow-bright: #fff5b1;
  --color-checks-ansi-blue: #79b8ff;
  --color-checks-ansi-blue-bright: #c8e1ff;
  --color-checks-ansi-magenta: #b392f0;
  --color-checks-ansi-magenta-bright: #d1bcf9;
  --color-checks-ansi-cyan: #76e3ea;
  --color-checks-ansi-cyan-bright: #b3f0ff;
  --color-intro-shelf-gradient-left: #f1f8ff;
  --color-intro-shelf-gradient-right: #dcffe4;
  --color-intro-shelf-gradient-in: #fff;
  --color-intro-shelf-gradient-out: rgba(255,255,255,0);
  --color-marketing-icon-primary: #2188ff;
  --color-marketing-icon-secondary: #79b8ff;
  --color-prettylights-syntax-comment: #6a737d;
  --color-prettylights-syntax-constant: #005cc5;
  --color-prettylights-syntax-entity: #6f42c1;
  --color-prettylights-syntax-storage-modifier-import: #24292e;
  --color-prettylights-syntax-entity-tag: #22863a;
  --color-prettylights-syntax-keyword: #d73a49;
  --color-prettylights-syntax-string: #032f62;
  --color-prettylights-syntax-variable: #e36209;
  --color-prettylights-syntax-brackethighlighter-unmatched: #b31d28;
  --color-prettylights-syntax-invalid-illegal-text: #fafbfc;
  --color-prettylights-syntax-invalid-illegal-bg: #b31d28;
  --color-prettylights-syntax-carriage-return-text: #fafbfc;
  --color-prettylights-syntax-carriage-return-bg: #d73a49;
  --color-prettylights-syntax-string-regexp: #22863a;
  --color-prettylights-syntax-markup-list: #735c0f;
  --color-prettylights-syntax-markup-heading: #005cc5;
  --color-prettylights-syntax-markup-italic: #24292e;
  --color-prettylights-syntax-markup-bold: #24292e;
  --color-prettylights-syntax-markup-deleted-text: #b31d28;
  --color-prettylights-syntax-markup-deleted-bg: #ffeef0;
  --color-prettylights-syntax-markup-inserted-text: #22863a;
  --color-prettylights-syntax-markup-inserted-bg: #f0fff4;
  --color-prettylights-syntax-markup-changed-text: #e36209;
  --color-prettylights-syntax-markup-changed-bg: #ffebda;
  --color-prettylights-syntax-markup-ignored-text: #f6f8fa;
  --color-prettylights-syntax-markup-ignored-bg: #005cc5;
  --color-prettylights-syntax-meta-diff-range: #6f42c1;
  --color-prettylights-syntax-brackethighlighter-angle: #586069;
  --color-prettylights-syntax-sublimelinter-gutter-mark: #959da5;
  --color-prettylights-syntax-constant-other-reference-link: #032f62;
  --color-codemirror-text: #24292e;
  --color-codemirror-bg: #fff;
  --color-codemirror-gutters-bg: #fff;
  --color-codemirror-guttermarker-text: #fff;
  --color-codemirror-guttermarker-subtle-text: #d1d5da;
  --color-codemirror-linenumber-text: #959da5;
  --color-codemirror-cursor: #24292e;
  --color-codemirror-selection-bg: #c8e1ff;
  --color-codemirror-activeline-bg: #fafbfc;
  --color-codemirror-matchingbracket-text: #24292e;
  --color-codemirror-lines-bg: #fff;
  --color-codemirror-syntax-comment: #6a737d;
  --color-codemirror-syntax-constant: #005cc5;
  --color-codemirror-syntax-entity: #6f42c1;
  --color-codemirror-syntax-keyword: #d73a49;
  --color-codemirror-syntax-storage: #d73a49;
  --color-codemirror-syntax-string: #032f62;
  --color-codemirror-syntax-support: #005cc5;
  --color-codemirror-syntax-variable: #e36209;
  --color-ansi-black: #24292e;
  --color-ansi-black-bright: #586069;
  --color-ansi-white: #6a737d;
  --color-ansi-white-bright: #959da5;
  --color-ansi-gray: #6a737d;
  --color-ansi-red: #d73a49;
  --color-ansi-red-bright: #cb2431;
  --color-ansi-green: #22863a;
  --color-ansi-green-bright: #28a745;
  --color-ansi-yellow: #b08800;
  --color-ansi-yellow-bright: #dbab09;
  --color-ansi-blue: #0366d6;
  --color-ansi-blue-bright: #2188ff;
  --color-ansi-magenta: #6f42c1;
  --color-ansi-magenta-bright: #8a63d2;
  --color-ansi-cyan: #1b7c83;
  --color-ansi-cyan-bright: #3192aa;
}

.markdown-body :root {
  color-scheme: light;
}

.markdown-body * {
  box-sizing: border-box;
}

.markdown-body input {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

.markdown-body a {
  color: var(--color-text-link);
  text-decoration: none;
}

.markdown-body a:hover {
  text-decoration: underline;
}

.markdown-body strong {
  font-weight: 600;
}

.markdown-body hr {
  background: transparent;
  border: 0;
  border-bottom: 1px solid var(--color-border-secondary);
  height: 0;
  margin: 15px 0;
  overflow: hidden;
}

.markdown-body hr:before {
  content: "";
  display: table;
}

.markdown-body hr:after {
  clear: both;
  content: "";
  display: table;
}

.markdown-body table {
  border-collapse: collapse;
  border-spacing: 0;
}

.markdown-body td,
.markdown-body th {
  padding: 0;
}

.markdown-body details summary {
  cursor: pointer;
}

.markdown-body kbd {
  background-color: var(--color-bg-secondary);
  border-bottom-color: var(--color-border-tertiary);
  border: 1px solid var(--color-border-tertiary);
  border-radius: 6px;
  box-shadow: inset 0 -1px 0 var(--color-border-tertiary);
  color: var(--color-text-primary);
  display: inline-block;
  font: 11px ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;
  line-height: 10px;
  padding: 3px 5px;
  vertical-align: middle;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  margin-bottom: 0;
  margin-top: 0;
}

.markdown-body h1 {
  font-size: 32px;
}

.markdown-body h1,
.markdown-body h2 {
  font-weight: 600;
}

.markdown-body h2 {
  font-size: 24px;
}

.markdown-body h3 {
  font-size: 20px;
}

.markdown-body h3,
.markdown-body h4 {
  font-weight: 600;
}

.markdown-body h4 {
  font-size: 16px;
}

.markdown-body h5 {
  font-size: 14px;
}

.markdown-body h5,
.markdown-body h6 {
  font-weight: 600;
}

.markdown-body h6 {
  font-size: 12px;
}

.markdown-body p {
  margin-bottom: 10px;
  margin-top: 0;
}

.markdown-body blockquote {
  margin: 0;
}

.markdown-body ol,
.markdown-body ul {
  margin-bottom: 0;
  margin-top: 0;
  padding-left: 0;
}

.markdown-body ol ol,
.markdown-body ul ol {
  list-style-type: lower-roman;
}

.markdown-body ol ol ol,
.markdown-body ol ul ol,
.markdown-body ul ol ol,
.markdown-body ul ul ol {
  list-style-type: lower-alpha;
}

.markdown-body dd {
  margin-left: 0;
}

.markdown-body code,
.markdown-body pre {
  font-family: ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;
  font-size: 12px;
}

.markdown-body pre {
  margin-bottom: 0;
  margin-top: 0;
}

.markdown-body input::-webkit-inner-spin-button,
.markdown-body input::-webkit-outer-spin-button {
  -webkit-appearance: none;
  appearance: none;
  margin: 0;
}

.markdown-body :checked+.radio-label {
  border-color: var(--color-border-info);
  position: relative;
  z-index: 1;
}

.markdown-body .border {
  border: 1px solid var(--color-border-primary)!important;
}

.markdown-body .border-0 {
  border: 0!important;
}

.markdown-body .border-bottom {
  border-bottom: 1px solid var(--color-border-primary)!important;
}

.markdown-body .rounded-1 {
  border-radius: 4px!important;
}

.markdown-body .color-text-tertiary {
  color: var(--color-text-tertiary)!important;
}

.markdown-body .color-bg-primary {
  background-color: var(--color-bg-primary)!important;
}

.markdown-body .color-bg-secondary {
  background-color: var(--color-bg-secondary)!important;
}

.markdown-body .mb-0 {
  margin-bottom: 0!important;
}

.markdown-body .my-2 {
  margin-bottom: 8px!important;
  margin-top: 8px!important;
}

.markdown-body .pl-0 {
  padding-left: 0!important;
}

.markdown-body .py-0 {
  padding-bottom: 0!important;
  padding-top: 0!important;
}

.markdown-body .pl-1 {
  padding-left: 4px!important;
}

.markdown-body .pl-2 {
  padding-left: 8px!important;
}

.markdown-body .py-2 {
  padding-bottom: 8px!important;
  padding-top: 8px!important;
}

.markdown-body .pl-3,
.markdown-body .px-3 {
  padding-left: 16px!important;
}

.markdown-body .px-3 {
  padding-right: 16px!important;
}

.markdown-body .pl-4 {
  padding-left: 24px!important;
}

.markdown-body .pl-5 {
  padding-left: 32px!important;
}

.markdown-body .pl-6 {
  padding-left: 40px!important;
}

.markdown-body .pl-7 {
  padding-left: 48px!important;
}

.markdown-body .pl-8 {
  padding-left: 64px!important;
}

.markdown-body .pl-9 {
  padding-left: 80px!important;
}

.markdown-body .pl-10 {
  padding-left: 96px!important;
}

.markdown-body .pl-11 {
  padding-left: 112px!important;
}

.markdown-body .pl-12 {
  padding-left: 128px!important;
}

.markdown-body .f6 {
  font-size: 12px!important;
}

.markdown-body .lh-condensed {
  line-height: 1.25!important;
}

.markdown-body .text-bold {
  font-weight: 600!important;
}

.markdown-body .pl-c {
  color: var(--color-prettylights-syntax-comment);
}

.markdown-body .pl-c1,
.markdown-body .pl-s .pl-v {
  color: var(--color-prettylights-syntax-constant);
}

.markdown-body .pl-e,
.markdown-body .pl-en {
  color: var(--color-prettylights-syntax-entity);
}

.markdown-body .pl-s .pl-s1,
.markdown-body .pl-smi {
  color: var(--color-prettylights-syntax-storage-modifier-import);
}

.markdown-body .pl-ent {
  color: var(--color-prettylights-syntax-entity-tag);
}

.markdown-body .pl-k {
  color: var(--color-prettylights-syntax-keyword);
}

.markdown-body .pl-pds,
.markdown-body .pl-s,
.markdown-body .pl-s .pl-pse .pl-s1,
.markdown-body .pl-sr,
.markdown-body .pl-sr .pl-cce,
.markdown-body .pl-sr .pl-sra,
.markdown-body .pl-sr .pl-sre {
  color: var(--color-prettylights-syntax-string);
}

.markdown-body .pl-smw,
.markdown-body .pl-v {
  color: var(--color-prettylights-syntax-variable);
}

.markdown-body .pl-bu {
  color: var(--color-prettylights-syntax-brackethighlighter-unmatched);
}

.markdown-body .pl-ii {
  background-color: var(--color-prettylights-syntax-invalid-illegal-bg);
  color: var(--color-prettylights-syntax-invalid-illegal-text);
}

.markdown-body .pl-c2 {
  background-color: var(--color-prettylights-syntax-carriage-return-bg);
  color: var(--color-prettylights-syntax-carriage-return-text);
}

.markdown-body .pl-c2:before {
  content: "^M";
}

.markdown-body .pl-sr .pl-cce {
  color: var(--color-prettylights-syntax-string-regexp);
  font-weight: 700;
}

.markdown-body .pl-ml {
  color: var(--color-prettylights-syntax-markup-list);
}

.markdown-body .pl-mh,
.markdown-body .pl-mh .pl-en,
.markdown-body .pl-ms {
  color: var(--color-prettylights-syntax-markup-heading);
  font-weight: 700;
}

.markdown-body .pl-mi {
  color: var(--color-prettylights-syntax-markup-italic);
  font-style: italic;
}

.markdown-body .pl-mb {
  color: var(--color-prettylights-syntax-markup-bold);
  font-weight: 700;
}

.markdown-body .pl-md {
  background-color: var(--color-prettylights-syntax-markup-deleted-bg);
  color: var(--color-prettylights-syntax-markup-deleted-text);
}

.markdown-body .pl-mi1 {
  background-color: var(--color-prettylights-syntax-markup-inserted-bg);
  color: var(--color-prettylights-syntax-markup-inserted-text);
}

.markdown-body .pl-mc {
  background-color: var(--color-prettylights-syntax-markup-changed-bg);
  color: var(--color-prettylights-syntax-markup-changed-text);
}

.markdown-body .pl-mi2 {
  background-color: var(--color-prettylights-syntax-markup-ignored-bg);
  color: var(--color-prettylights-syntax-markup-ignored-text);
}

.markdown-body .pl-mdr {
  color: var(--color-prettylights-syntax-meta-diff-range);
  font-weight: 700;
}

.markdown-body .pl-ba {
  color: var(--color-prettylights-syntax-brackethighlighter-angle);
}

.markdown-body .pl-sg {
  color: var(--color-prettylights-syntax-sublimelinter-gutter-mark);
}

.markdown-body .pl-corl {
  color: var(--color-prettylights-syntax-constant-other-reference-link);
  text-decoration: underline;
}

.markdown-body .HeaderMenu-summary::marker {
  display: none;
}

.markdown-body :root {
  --border-width: 1px;
  --border-style: solid;
  --font-size-small: 12px;
  --font-weight-semibold: 500;
  --size-2: 20px;
}

.markdown-body kbd {
  background-color: var(--color-bg-secondary);
  border-bottom-color: var(--color-border-tertiary);
  border: 1px solid var(--color-border-tertiary);
  border-radius: 6px;
  box-shadow: inset 0 -1px 0 var(--color-border-tertiary);
  color: var(--color-text-primary);
  display: inline-block;
  font: 11px ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;
  line-height: 10px;
  padding: 3px 5px;
  vertical-align: middle;
}

.markdown-body:before {
  content: "";
  display: table;
}

.markdown-body:after {
  clear: both;
  content: "";
  display: table;
}

.markdown-body>:first-child {
  margin-top: 0!important;
}

.markdown-body>:last-child {
  margin-bottom: 0!important;
}

.markdown-body a:not([href]) {
  color: inherit;
  text-decoration: none;
}

.markdown-body blockquote,
.markdown-body details,
.markdown-body dl,
.markdown-body ol,
.markdown-body p,
.markdown-body pre,
.markdown-body table,
.markdown-body ul {
  margin-bottom: 16px;
  margin-top: 0;
}

.markdown-body hr {
  background-color: var(--color-border-primary);
  border: 0;
  height: .25em;
  margin: 24px 0;
  padding: 0;
}

.markdown-body blockquote {
  border-left: .25em solid var(--color-markdown-blockquote-border);
  color: var(--color-text-tertiary);
  padding: 0 1em;
}

.markdown-body blockquote>:first-child {
  margin-top: 0;
}

.markdown-body blockquote>:last-child {
  margin-bottom: 0;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  font-weight: 600;
  line-height: 1.25;
  margin-bottom: 16px;
  margin-top: 24px;
}

.markdown-body h1 {
  font-size: 2em;
}

.markdown-body h1,
.markdown-body h2 {
  border-bottom: 1px solid var(--color-border-secondary);
  padding-bottom: .3em;
}

.markdown-body h2 {
  font-size: 1.5em;
}

.markdown-body h3 {
  font-size: 1.25em;
}

.markdown-body h4 {
  font-size: 1em;
}

.markdown-body h5 {
  font-size: .875em;
}

.markdown-body h6 {
  color: var(--color-text-tertiary);
  font-size: .85em;
}

.markdown-body ol,
.markdown-body ul {
  padding-left: 2em;
}

.markdown-body ol ol,
.markdown-body ol ul,
.markdown-body ul ol,
.markdown-body ul ul {
  margin-bottom: 0;
  margin-top: 0;
}

.markdown-body li>p {
  margin-top: 16px;
}

.markdown-body li+li {
  margin-top: .25em;
}

.markdown-body dl {
  padding: 0;
}

.markdown-body dl dt {
  font-size: 1em;
  font-style: italic;
  font-weight: 600;
  margin-top: 16px;
  padding: 0;
}

.markdown-body dl dd {
  margin-bottom: 16px;
  padding: 0 16px;
}

.markdown-body table {
  display: block;
  max-width: 100%;
  overflow: auto;
  width: 100%;
  width: -webkit-max-content;
  width: -moz-max-content;
  width: max-content;
}

.markdown-body table th {
  font-weight: 600;
}

.markdown-body table td,
.markdown-body table th {
  border: 1px solid var(--color-markdown-table-border);
  padding: 6px 13px;
}

.markdown-body table tr {
  background-color: var(--color-bg-primary);
  border-top: 1px solid var(--color-markdown-table-tr-border);
}

.markdown-body table tr:nth-child(2n) {
  background-color: var(--color-bg-tertiary);
}

.markdown-body img {
  background-color: var(--color-bg-primary);
  box-sizing: content-box;
  max-width: 100%;
}

.markdown-body img[align=right] {
  padding-left: 20px;
}

.markdown-body img[align=left] {
  padding-right: 20px;
}

.markdown-body code {
  background-color: var(--color-markdown-code-bg);
  border-radius: 6px;
  font-size: 85%;
  margin: 0;
  padding: .2em .4em;
}

.markdown-body pre {
  word-wrap: normal;
}

.markdown-body pre>code {
  background: transparent;
  border: 0;
  font-size: 100%;
  margin: 0;
  padding: 0;
  white-space: pre;
  word-break: normal;
}

.markdown-body .highlight {
  margin-bottom: 16px;
}

.markdown-body .highlight pre {
  margin-bottom: 0;
  word-break: normal;
}

.markdown-body .highlight pre,
.markdown-body pre {
  background-color: var(--color-bg-tertiary);
  border-radius: 6px;
  font-size: 85%;
  line-height: 1.45;
  overflow: auto;
  padding: 16px;
}

.markdown-body pre code {
  word-wrap: normal;
  background-color: transparent;
  border: 0;
  display: inline;
  line-height: inherit;
  margin: 0;
  max-width: auto;
  overflow: visible;
  padding: 0;
}

.markdown-body .commit-tease-sha {
  color: var(--color-text-primary);
  display: inline-block;
  font-family: ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;
  font-size: 90%;
}

.markdown-body .blob-wrapper {
  overflow-x: auto;
  overflow-y: hidden;
}

.markdown-body .blob-wrapper table tr:nth-child(2n) {
  background-color: transparent;
}

.markdown-body .blob-wrapper-embedded {
  max-height: 240px;
  overflow-y: auto;
}

.markdown-body .blob-num {
  color: var(--color-diff-blob-num-text);
  cursor: pointer;
  font-family: ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;
  font-size: 12px;
  line-height: 20px;
  min-width: 50px;
  padding-left: 10px;
  padding-right: 10px;
  text-align: right;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  vertical-align: top;
  white-space: nowrap;
  width: 1%;
}

.markdown-body .blob-num:hover {
  color: var(--color-diff-blob-num-hover-text);
}

.markdown-body .blob-num:before {
  content: attr(data-line-number);
}

.markdown-body .blob-code {
  line-height: 20px;
  padding-left: 10px;
  padding-right: 10px;
  position: relative;
  vertical-align: top;
}

.markdown-body .blob-code-inner {
  word-wrap: normal;
  color: var(--color-text-primary);
  font-family: ui-monospace,SFMono-Regular,SF Mono,Menlo,Consolas,Liberation Mono,monospace;
  font-size: 12px;
  overflow: visible;
  white-space: pre;
}

.markdown-body .blob-code-inner::selection,
.markdown-body .blob-code-inner ::selection {
  background-color: var(--color-code-selection-bg);
}

.markdown-body .pl-token.active,
.markdown-body .pl-token:hover {
  background: #ffea7f;
  cursor: pointer;
}

.markdown-body :root {
  --color-social-reaction-border: var(--color-scale-blue-1);
  --color-social-reaction-bg: var(--color-scale-gray-0);
  --color-social-reaction-bg-hover: var(--color-scale-gray-1);
  --color-social-reaction-bg-reacted-hover: var(--color-scale-blue-1);
}

.markdown-body .social-reaction-summary-item:focus-visible {
  box-shadow: var(--color-state-focus-shadow);
  outline: 0;
}

.markdown-body .emoji-picker-tab .btn-outline:not(:hover) {
  background-color: transparent;
}

.markdown-body .task-list-item {
  list-style-type: none;
}

.markdown-body .task-list-item+.task-list-item {
  margin-top: 3px;
}

.markdown-body .task-list-item input {
  margin: 0 .2em .25em -1.6em;
  vertical-align: middle;
}

.markdown-body .AvatarStack-body:not(:hover) {
  background-color: transparent;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover) .avatar:nth-of-type(n+6) {
  display: none;
  opacity: 0;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more+.avatar:nth-of-type(3) img {
  opacity: .5;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(4) img {
  opacity: .33;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(5) img {
  opacity: .25;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more+.avatar:nth-of-type(3) {
  margin-left: -6px;
  margin-right: 0;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(4) {
  margin-left: -18px;
  margin-right: 0;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(5) {
  margin-left: -18px;
  margin-right: 0;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus.AvatarStack--right .AvatarStack-body:not(:hover)>.avatar-more+.avatar:nth-of-type(3) {
  margin-left: 0;
  margin-right: -6px;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus.AvatarStack--right .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(4) {
  margin-left: 0;
  margin-right: -18px;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus.AvatarStack--right .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(5) {
  margin-left: 0;
  margin-right: -18px;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus.AvatarStack--large .AvatarStack-body:not(:hover)>.avatar-more+.avatar:nth-of-type(3) {
  margin-left: -2px;
  margin-right: 0;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus.AvatarStack--large .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(4) {
  margin-left: -30px;
  margin-right: 0;
}

.markdown-body .AvatarStack--three-plus.AvatarStack--three-plus.AvatarStack--large .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(5) {
  margin-left: -30px;
  margin-right: 0;
}

.markdown-body .hx_avatar_stack_commit .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more+.avatar:nth-of-type(3) {
  margin-left: -10px;
  margin-right: 0;
}

.markdown-body .hx_avatar_stack_commit .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(4) {
  margin-left: -21px;
  margin-right: 0;
}

.markdown-body .hx_avatar_stack_commit .AvatarStack--three-plus.AvatarStack--three-plus .AvatarStack-body:not(:hover)>.avatar-more~.avatar:nth-of-type(5) {
  margin-left: -21px;
  margin-right: 0;
}

.markdown-body :root {
  --color-workflow-card-connector: var(--color-scale-gray-3);
  --color-workflow-card-connector-bg: var(--color-scale-gray-3);
  --color-workflow-card-connector-inactive: var(--color-border-primary);
  --color-workflow-card-connector-inactive-bg: var(--color-border-primary);
  --color-workflow-card-connector-highlight: var(--color-scale-blue-4);
  --color-workflow-card-connector-highlight-bg: var(--color-scale-blue-4);
  --color-workflow-card-bg: var(--color-scale-white);
  --color-workflow-card-inactive-bg: var(--color-bg-canvas-inset);
  --color-workflow-card-header-shadow: transparent;
  --color-workflow-card-progress-complete-bg: var(--color-scale-blue-4);
  --color-workflow-card-progress-incomplete-bg: var(--color-scale-gray-2);
  --color-discussions-answer-border: var(--color-scale-green-5);
  --color-discussions-answer-icon: var(--color-scale-green-6);
  --color-discussions-answer-text: var(--color-scale-green-6);
  --color-discussions-state-answered-icon: var(--color-scale-white);
  --color-bg-discussions-row-emoji-box: rgba(209,213,218,0.5);
  --color-upvote-icon-bg: var(--color-accent-subtle,var(--color-scale-blue-1));
  --color-downvote-icon-bg: var(--color-scale-red-1);
  --color-search-hover-hl: var(--color-scale-white);
  --color-notifications-button-text: var(--color-text-secondary);
  --color-notifications-button-hover-text: var(--color-text-primary);
  --color-notifications-button-hover-bg: var(--color-scale-gray-2);
  --color-notifications-row-read-bg: var(--color-bg-tertiary);
  --color-notifications-row-bg: var(--color-scale-white);
  --color-page-header-bg: var(--color-bg-secondary);
  --color-timeline-merged-bg: var(--color-scale-purple-5);
  --color-icon-directory: var(--color-scale-blue-3);
  --color-calendar-halloween-graph-day-L1-bg: #ffee4a;
  --color-calendar-halloween-graph-day-L2-bg: #ffc501;
  --color-calendar-halloween-graph-day-L3-bg: #fe9600;
  --color-calendar-halloween-graph-day-L4-bg: #03001c;
  --color-calendar-graph-day-bg: #ebedf0;
  --color-calendar-graph-day-border: rgba(27,31,35,0.06);
  --color-calendar-graph-day-L1-bg: #9be9a8;
  --color-calendar-graph-day-L2-bg: #40c463;
  --color-calendar-graph-day-L3-bg: #30a14e;
  --color-calendar-graph-day-L4-bg: #216e39;
  --color-calendar-graph-day-L1-border: rgba(27,31,35,0.06);
  --color-calendar-graph-day-L2-border: rgba(27,31,35,0.06);
  --color-calendar-graph-day-L3-border: rgba(27,31,35,0.06);
  --color-calendar-graph-day-L4-border: rgba(27,31,35,0.06);
  --color-text-white: var(--color-scale-white);
}

.markdown-body :checked+.hx_theme-toggle {
  border-color: var(--color-state-hover-primary-border);
}

.markdown-body ::-webkit-calendar-picker-indicator {
  filter: invert(50%);
}

.markdown-body .rounded-1 {
  border-radius: 6px!important;
}

.markdown-body .hx_disabled-input input:not(:disabled) {
  margin-bottom: 8px!important;
  margin-top: 8px!important;
}

.markdown-body :root {
  --border-width: 1px;
  --border-style: solid;
  --font-size-small: 12px;
  --font-weight-semibold: 500;
  --size-2: 20px;
}

.markdown-body :focus+.radio-label-theme-discs {
  border-color: var(--color-state-focus-border);
  box-shadow: var(--color-state-focus-shadow);
  outline: none;
}

.markdown-body :checked+.radio-label-theme-discs {
  border-color: var(--color-state-selected-primary-border);
}

.markdown-body :checked+.radio-label-theme-discs {
  padding: 8px;
}

.markdown-body .tab-size[data-tab-size="1"] {
  -moz-tab-size: 1;
  tab-size: 1;
}

.markdown-body .tab-size[data-tab-size="2"] {
  -moz-tab-size: 4;
  tab-size: 4;
}

.markdown-body .tab-size[data-tab-size="3"] {
  -moz-tab-size: 6;
  tab-size: 6;
}

.markdown-body .tab-size[data-tab-size="4"] {
  -moz-tab-size: 4;
  tab-size: 4;
}

.markdown-body .tab-size[data-tab-size="5"] {
  -moz-tab-size: 5;
  tab-size: 5;
}

.markdown-body .tab-size[data-tab-size="6"] {
  -moz-tab-size: 6;
  tab-size: 6;
}

.markdown-body .tab-size[data-tab-size="7"] {
  -moz-tab-size: 7;
  tab-size: 7;
}

.markdown-body .tab-size[data-tab-size="8"] {
  -moz-tab-size: 8;
  tab-size: 8;
}

.markdown-body .tab-size[data-tab-size="9"] {
  -moz-tab-size: 9;
  tab-size: 9;
}

.markdown-body .tab-size[data-tab-size="10"] {
  -moz-tab-size: 10;
  tab-size: 10;
}

.markdown-body .tab-size[data-tab-size="11"] {
  -moz-tab-size: 11;
  tab-size: 11;
}

.markdown-body .tab-size[data-tab-size="12"] {
  -moz-tab-size: 12;
  tab-size: 12;
}

.markdown-body :root {
  --border-width: 1px;
  --border-style: solid;
  --font-size-small: 12px;
  --font-weight-semibold: 500;
  --size-2: 20px;
}

.markdown-body .faq-mktg summary::marker {
  display: none!important;
}

.markdown-body :root {
  --border-width: 1px;
  --border-style: solid;
  --font-size-small: 12px;
  --font-weight-semibold: 500;
  --size-2: 20px;
}
</style>







<article class="markdown-body">
	<h1>Unicorns</h1>
	<p>All the things</p>
</article>

> The minimal amount of CSS to replicate the GitHub Markdown style

[<img src="https://cloud.githubusercontent.com/assets/170270/5219062/f22a978c-7685-11e4-8316-af25b6c89bc0.png" width="300">](http://bgoonz.com/github-markdown-css)

## [Demo](https://bgoonz.com/github-markdown-css)

## Install

> with npm:

```sh
 npm install github-markdown-css
```

## Usage

Import the `github-markdown.css` file and add a `markdown-body` class to the container of your rendered Markdown and set a width for it. GitHub uses `980px` width and `45px` padding, and `15px` padding for mobile.

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="github-markdown.css">
<style>
	.markdown-body {
		box-sizing: border-box;
		min-width: 200px;
		max-width: 980px;
		margin: 0 auto;
		padding: 45px;
	}

	@media (max-width: 767px) {
		.markdown-body {
			padding: 15px;
		}
	}
</style>
<article class="markdown-body">
	<h1>Unicorns</h1>
	<p>All the things</p>
</article>
```

If you want code syntax highlighted, use GitHub Flavored Markdown rendered from [GitHub's `/markdown` API](https://docs.github.com/en/free-pro-team@latest/rest/reference/markdown).

## How

See [`generate-github-markdown-css`](https://github.com/bgoonz/generate-github-markdown-css) for how it's generated and ability to generate your own.

## Dev

Run `npm run make` to update the CSS.
