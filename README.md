# Confluence Server: Built-in column names 

[![Atlassian license](https://img.shields.io/badge/license-Apache%202.0-blue.svg?style=flat-square)](LICENSE)

This is to grant the Apache 2.0 license to the below snippet of Confluence Server. 

Unless you've been explicitly pointed to this repository, you likely won't need it. ✌️

```java
private static final Set<String> ALL_BUILTIN_COLUMN_NAMES =
    Collections.unmodifiableSet(
        new HashSet<>(
            Arrays.asList(
                “description”,
                “environment”,
                “key”,
                “summary”,
                “type”,
                “parent”,
                “creator”,
                “project”,
                “priority”,
                “status”,
                “version”,
                “resolution”,
                “security”,
                “assignee”,
                “reporter”,
                “created”,
                “updated”,
                “due”,
                “component”,
                “components”,
                “votes”,
                “comments”,
                “attachments”,
                “subtasks”,
                “fixversion”,
                “timeoriginalestimate”,
                “timeestimate”,
                “statuscategory”
            )
        )
    );
```

## License

Copyright (c) 2020 Atlassian and others.
Apache 2.0 licensed, see [LICENSE](LICENSE) file.

<br/> 

[![With ❤️ from Atlassian](https://raw.githubusercontent.com/atlassian-internal/oss-assets/master/banner-cheers.png)](https://www.atlassian.com)