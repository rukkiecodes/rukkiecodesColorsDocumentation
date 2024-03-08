<template>
    <h3 class="mt-10">Blue</h3>
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
                <td>{{ blue50.name }}</td>
                <td>{{ blue50.hex }}</td>
                <td>
                    <v-sheet :color="blue50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue100.name }}</td>
                <td>{{ blue100.hex }}</td>
                <td>
                    <v-sheet :color="blue100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue200.name }}</td>
                <td>{{ blue200.hex }}</td>
                <td>
                    <v-sheet :color="blue200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue300.name }}</td>
                <td>{{ blue300.hex }}</td>
                <td>
                    <v-sheet :color="blue300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue400.name }}</td>
                <td>{{ blue400.hex }}</td>
                <td>
                    <v-sheet :color="blue400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue500.name }}</td>
                <td>{{ blue500.hex }}</td>
                <td>
                    <v-sheet :color="blue500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue600.name }}</td>
                <td>{{ blue600.hex }}</td>
                <td>
                    <v-sheet :color="blue600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue700.name }}</td>
                <td>{{ blue700.hex }}</td>
                <td>
                    <v-sheet :color="blue700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue800.name }}</td>
                <td>{{ blue800.hex }}</td>
                <td>
                    <v-sheet :color="blue800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ blue900.name }}</td>
                <td>{{ blue900.hex }}</td>
                <td>
                    <v-sheet :color="blue900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    blue50,
    blue100,
    blue200,
    blue300,
    blue400,
    blue500,
    blue600,
    blue700,
    blue800,
    blue900,
} from 'rukkiecodes-colors';
</script>
