# Auto Self Report

## Usage

After forking, add secrets at your own repository's <a href="../../settings/secrets">Settings-Secrets</a>

- `SHU_USERNAME`: 一卡通账号
- `SHU_PASSWORD`: 一卡通密码
- `EMAIL`: 用于接收通知的邮箱

⚠️ NOTE: according to the [conversation in the GitHub Community](https://github.community/t5/GitHub-Actions/Forked-repo-doesn-t-trigger-action/m-p/32575#M1189), you should copy the contents of the `report.yml`, delete the file, and create a new file with the same name and contents as the original `report.yml`, and then job will run at 9 a.m. every day.


