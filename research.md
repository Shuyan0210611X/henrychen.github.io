/* Force ordered lists to show 1. 2. 3. (not [1]) */
.page-content ol,
.post-content ol,
.page__content ol,
.archive ol {
  list-style: decimal !important;
  margin-left: 1.4rem !important;
  padding-left: 0 !important;
}

.page-content ol li,
.post-content ol li,
.page__content ol li,
.archive ol li {
  display: list-item !important;
  margin: 0.45rem 0 !important;
  line-height: 1.55;
}

/* Remove theme-injected bracket numbering like [1] */
.page-content ol li::before,
.post-content ol li::before,
.page__content ol li::before,
.archive ol li::before {
  content: none !important;
}
