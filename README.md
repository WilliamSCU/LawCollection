# LawCollection
## Json格式法律集，以及使用text-embedding-ada-002嵌入后的结果
### 示例：
```json
{
        "id": "1", //编号
        "law_name": "中华人民共和国民法典总则", //法律名
        "chapter": "第一章 基本规定", //章
        "section": "",  //节，可能为空
        "article_number": "第一条", //条
        "content": "为了保护民事主体的合法权益，调整民事关系，维护社会和经济秩序，适应中国特色社会主义发展要求，弘扬社会主义核心价值观，根据宪法，制定本法。"  //条款内容
        "embedding": [] //调用openAI的text-embedding-ada-002将条款内容转换为1536维的嵌入向量
        
}
```
