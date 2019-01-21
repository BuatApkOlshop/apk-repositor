curl https://api.github.com/zen
Keep it logically awesome.
 # GET /users/defunkt
curl https://api.github.com/users/defunkt
{
  "login": "defunkt",
  "id": 2,
  "url": "https://api.github.com/users/defunkt",
  "html_url": "https://github.com/defunkt",
  ...
}

JESSON#####

 curl -i https://api.github.com/users/defunkt
HTTP/1.1 200 OK
Server: GitHub.com
Date: Sun, 11 Nov 2012 18:43:28 GMT
Content-Type: application/json; charset=utf-8
Connection: keep-alive
Status: 200 OK
ETag: "bfd85cbf23ac0b0c8a29bee02e7117c6"
X-RateLimit-Limit: 60
X-RateLimit-Remaining: 57
X-RateLimit-Reset: 1352660008
X-GitHub-Media-Type: github.v3
Vary: Accept
Cache-Control: public, max-age=60, s-maxage=60
X-Content-Type-Options: nosniff
Content-Length: 692
Last-Modified: Tue, 30 Oct 2012 18:58:42 GMT
{
  "login": "defunkt",
  "id": 2,
  "url": "https://api.github.com/users/defunkt",
  "html_url": "https://github.com/defunkt",
  ...
}
