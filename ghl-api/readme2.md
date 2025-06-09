import os

# Path to default README.md
readme_path = "README.md"

# Remove it if it exists
if os.path.exists(readme_path):
    os.remove(readme_path)
    print("🗑️ Removed 'README.md'")

print("✅ 'readme2.md' is now the official and only README.")
