# easy-wrangler
Copy and paste for deploying cloudflare workers on github

# 使用说明
修改如下文件：
1. .github\workflows\deploy.yaml `branches, "worker.js"`
2. .github\workflows\stage.yaml `branches, "worker.js"`
3. .github\workflows\sync.yaml `upstream_sync_repo, upstream_sync_branch, target_sync_branch`
4. wrangler.toml `name, routes`
5. Actions secrets and variables > Repository secrets > add `CF_ACCOUNT_ID, CF_API_TOKEN, CLOUDFLARE_ACCOUNT_ID, CLOUDFLARE_API_TOKEN`

# Usage Instructions
Modify the following files:
1. .github\workflows\deploy.yaml `branches, "worker.js"`
2. .github\workflows\stage.yaml `branches, "worker.js"`
3. .github\workflows\sync.yaml `upstream_sync_repo, upstream_sync_branch, target_sync_branch`
4. wrangler.toml `name, routes`
5. Actions secrets and variables > Repository secrets > add `CF_ACCOUNT_ID, CF_API_TOKEN, CLOUDFLARE_ACCOUNT_ID, CLOUDFLARE_API_TOKEN`
