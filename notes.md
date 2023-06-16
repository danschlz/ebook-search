Notes on usage:

Make sure to change runtime to GPU.
Upload an epub file representing the ebook you want to search (tip: ever heard of libgen?).
Re-run the last cell using different queries to keep searching the same book.
Optional:

Embeddings for the book you upload will be saved in Files (in the left menu bar) under the title 'embeddings-{first chapter}-{last chapter}-{model name}-{epub filename}.json'.
Download this file and upload it (instead of an epub) on your next runtime session in order to avoid generating the embeddings again.
Run 'process_file' with 'preview_mode' set to True at first to check which range of chapters you want to index. This helps you avoid needlessly creating embeddings for chapters like 'Notes' and 'Works Cited"