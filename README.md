.tab-border-top-container {
  -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  mask-composite: xor;
  -webkit-mask-composite: xor;
  mask-composite: exclude;
  padding: 1.3px;
  width: 100% !important;
  height: calc(100% - 3px) !important;
  background-color: transparent !important;
  border-radius: 10px;
  filter: drop-shadow(0 0 10px #adbbff);
}

.tab-border-top-container:before {
  content: "";
  width: 500px;
  height: 500px;
  position: absolute;
  left: 50%;
  top: 50%;
  border-radius: inherit;
  transform: translate(-50%, -50%);
  animation: spinner 5s cubic-bezier(0.25, 0.46, 0.45, 0.94) infinite;
  background: conic-gradient(from 0deg at 50% 51.35%,
      rgba(185, 215, 243, 0) 0deg,
      rgba(185, 215, 243, 0) 289.4deg,
      #ffb86c 318.05deg,
      #ff65f2 1turn),
    conic-gradient(from 180deg at 50% 51.35%,
      rgba(185, 215, 243, 0) 0deg,
      rgba(185, 215, 243, 0) 287.46deg,
      #20e3b2 325.02deg,
      #00aefd 1turn);
}

@keyframes spinner {
  100% {
    transform: translate(-50%, -50%) rotate(1turn);
  }
}

.monaco-decoration-itemBadge--qbi6iu::after {
  content: "1";
  color: aquamarine;
}
.monaco-pane-view .split-view-view:first-of-type>.pane>.pane-header  {

  animation: colorAnimation 5s infinite;

}
.tab.active  {
  border-radius: 10px !important;
  box-shadow: inset 0 1px 1px 0 rgba(199, 211, 234, 0.12),
    inset 0 24px 48px 0 rgba(199, 211, 234, 0.05),
    0 24px 32px 0 rgba(6, 6, 14, 0.7);
  animation: colorAnimation 5s infinite;

}
.monaco-workbench .part.editor>.content .editor-group-container.active>.title .tabs-container>.tab>.tab-actions .action-label.codicon:hover {

  box-shadow: inset 0 1px 1px 0 rgb(199 211 234 / 12%), inset 0 24px 48px 0 rgb(199 211 234 / 5%), 0 24px 32px 0 rgb(6 6 14 / 70%);
}

.monaco-workbench .part.editor>.content .editor-group-container.active>.title .tabs-container>.tab.active>.tab-actions .action-label.codicon {

  box-shadow: inset 0 1px 1px 0 rgb(199 211 234 / 12%), inset 0 24px 48px 0 rgb(199 211 234 / 5%), 0 24px 32px 0 rgb(6 6 14 / 70%);
}

.tab.active .label-name {
  font-size: 13.5px !important;

}

@keyframes shine {
  to {
    background-position: 200% center;
  }
}

@keyframes colorAnimation {
  0% {
    color: #ff65f2;
  }

  25% {
    color: #87CEEB;
  }

  50% {
    color: #20e3b2;

  }

  75% {
    color: #5be2dc;
  }

  100% {
    color: #ff65f2;
  }
}

.show-file-icons .monaco-tl-twistie.collapsible:not(.collapsed)+.monaco-tl-contents .folder-icon::before {
  content: ' ';
  background-image: url(https://media-public.canva.com/f4vwU/MAF-exf4vwU/1/t.png);

}

.codicon-tree-item-expanded:before {
  content: '3';
  font-size: 1px;
  background-image: url('https://media-public.canva.com/eCgGY/MAEWMNeCgGY/1/t.png');
  background-repeat: no-repeat;
  background-size: 11px;
  display: inline-block;
  width: 11px;
  height: 11px;

}

.show-file-icons .folder-icon::before {
  content: ' ';
  background-image: url(https://media-public.canva.com/e8dTI/MAFoUWe8dTI/1/t.png);

}
