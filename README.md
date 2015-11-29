# テーブル定義
## Users
- name: string
- email: string
- password: string
- organization: string
- profile: text
- works: string
- photo:  text

## Prototypes
- user_id: integer
- catchcopy: string
- concept: text

## Images
- prototype_id
- image: text

## Likes
- prototype_id
- user_id

## Tags
- tag: string

## Comments
- user_id: integer
- prototype_id: integer
- comment: text