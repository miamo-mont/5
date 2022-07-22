# 5
int main()
{
	int ret = 0;
	char password[20]= {0};
	printf("请输入密码:", password);
	scanf("%s", password);
	getchar();
	printf("请确认\n");
	ret = getchar();
		if (ret = 'Y')
		{
			printf("确认成功\n");
		}
		else
		{
			printf("确认失败\n");
		}

}
