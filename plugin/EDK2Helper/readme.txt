字符串  L"" ""                         C语言中的字符串颜色
数字:   0x00 && 0x00000000             淡绿色
备注    #  备注内容  // 备注内容       绿色
模块    [sssss]                        C语言中函数的名字
条件    !开头                          

            <dict>
                <key>name</key>
                <string>keyword.control.dec</string>
                <key>match</key>
                <string>(\s\s[A-Z_].*\s)(=)(\s\S*)</string>
            </dict>






            <dict>
                <key>match</key>
                <string>(\s\s[A-Z_].*\s)(=)(\s\S*)</string>
                <key>cpatures</key>
                <dict>
                    <key>1</key>
                    <dict>
                        <key>name</key>
                        <string>keyword.control.dec</string>
                    </dict>
                    <key>3</key>
                    <dict>
                        <key>name</key>
                        <string>comment.line.dec</string>
                    </dict>
                </dict>
            </dict>




                <dict>
                <key>match</key>
                <string>(.*)(\|)(.*)</string>
                <key>captures</key>
                <dict>
                    <key>1</key>
                    <dict>
                        <key>name</key>
                        <string>keyword.control.dec</string>
                    </dict>
                    <key>3</key>
                    <dict>
                        <key>name</key>
                        <string>comment.line.dec</string>
                    </dict>
                </dict>
            </dict>