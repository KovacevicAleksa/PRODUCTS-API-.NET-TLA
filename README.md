CREATE TABLE [dbo].[Products] (<br/>
    [Id] INT IDENTITY (1, 1) NOT NULL,<br/>
    [Name] NVARCHAR (50) NOT NULL,<br/>
    [Description] NVARCHAR (100) NOT NULL,<br/>
    [Price] DECIMAL (18) NOT NULL,<br/>
    PRIMARY KEY CLUSTERED ([Id] ASC)<br/>
);
