CREATE TABLE [dbo].[Products] (\n
    [Id] INT IDENTITY (1, 1) NOT NULL,\n
    [Name] NVARCHAR (50) NOT NULL,\n
    [Description] NVARCHAR (100) NOT NULL,\n
    [Price] DECIMAL (18) NOT NULL,\n
    PRIMARY KEY CLUSTERED ([Id] ASC)\n
);
