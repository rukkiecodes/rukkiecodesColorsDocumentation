<template>
    <h3 class="mt-10">Off white</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ offWhite50.name }}</td>
                <td>{{ offWhite50.hex }}</td>
                <td>
                    <v-sheet :color="offWhite50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite100.name }}</td>
                <td>{{ offWhite100.hex }}</td>
                <td>
                    <v-sheet :color="offWhite100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite200.name }}</td>
                <td>{{ offWhite200.hex }}</td>
                <td>
                    <v-sheet :color="offWhite200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite300.name }}</td>
                <td>{{ offWhite300.hex }}</td>
                <td>
                    <v-sheet :color="offWhite300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite400.name }}</td>
                <td>{{ offWhite400.hex }}</td>
                <td>
                    <v-sheet :color="offWhite400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite500.name }}</td>
                <td>{{ offWhite500.hex }}</td>
                <td>
                    <v-sheet :color="offWhite500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite600.name }}</td>
                <td>{{ offWhite600.hex }}</td>
                <td>
                    <v-sheet :color="offWhite600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite700.name }}</td>
                <td>{{ offWhite700.hex }}</td>
                <td>
                    <v-sheet :color="offWhite700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite800.name }}</td>
                <td>{{ offWhite800.hex }}</td>
                <td>
                    <v-sheet :color="offWhite800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ offWhite900.name }}</td>
                <td>{{ offWhite900.hex }}</td>
                <td>
                    <v-sheet :color="offWhite900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    offWhite50,
    offWhite100,
    offWhite200,
    offWhite300,
    offWhite400,
    offWhite500,
    offWhite600,
    offWhite700,
    offWhite800,
    offWhite900,
} from 'rukkiecodes-colors';
</script>
