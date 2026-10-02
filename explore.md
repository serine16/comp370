# How big is the dataset?
The dataset file size is 4.5 MB, with 36,860 lines.

# What's the strcuture of the data?  (i.e., what are the field and what are values in them)
- 4 comma-seperated fields: title, writer, pony and dialog.
- The values include string descriptions for episode names and writers, character names in the pony column, and full text strings of spoken lines in the dialog column.

# How many episodes does it cover?
197 unique episodes

# During the exploration phase, find at least one aspect of the dataset that is unexpected – meaning that it seems like it could create issues for later analysis.
- Some rows contain combined character names in the pony field (e.g., "Narrator and Twilight Sparkle"), which requires careful parsing rather than simple exact-match queries.

- The text contains raw Unicode control characters and escape codes (such as <U+0096>), which may cause encoding or text-cleaning issues during natural language processing tasks.
