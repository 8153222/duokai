仅供学习交流，禁止用于商业用途。

远程配置
YD 可以通过远程 JSON 文件批量应用设置。默认下载地址在 YDConstants.h 中的 DYYY_REMOTE_CONFIG_URL。配置文件示例：
{
    "mode": "YD_MODE_PATCH",
    "data": {
        "ExampleKey": true
    }
}
mode 字段可选，支持 DYYY_MODE_PATCH 和 DYYY_MODE_REPLACE，若省略则默认为补丁模式 (DYYY_MODE_PATCH)。
