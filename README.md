{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "VisualEditor0",
            "Effect": "Allow",
            "Action": [
                "iam:CreateGroup",
                "iam:GetPolicy",
                "iam:DeleteGroup",
                "iam:DeleteUserPolicy",
                "iam:CreateUser",
                "iam:TagUser",
                "iam:UntagUser",
                "iam:AttachGroupPolicy",
                "iam:GetUser",
                "iam:DetachUserPolicy",
                "iam:DeleteLoginProfile",
                "iam:ChangePassword",
                "iam:ListUserTags"
            ],
            "Resource": "arn:aws:iam::126148273178:group/*"
        },
        {
            "Sid": "VisualEditor1",
            "Effect": "Allow",
            "Action": [
                "iam:GetAccountName",
                "iam:ListUsers",
                "iam:ListGroups"
            ],
            "Resource": "*"
        }
    ]
}
